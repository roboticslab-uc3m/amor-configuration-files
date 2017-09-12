add_subdirectory(amorBase)
add_subdirectory(amorSimBase)
add_subdirectory(amorTools)
add_subdirectory(kinematics)

yarp_install(FILES ymanager.ini
             DESTINATION ${AMOR_APPLICATIONS_INSTALL_DIR})

yarp_install(FILES yarpmotorgui/amor-yarpmotorgui.ini
             DESTINATION ${AMOR_APPLICATIONS_INSTALL_DIR})

yarp_install(FILES ${CMAKE_SOURCE_DIR}/doc/fig/RL_logo_64x64.png
             DESTINATION ${AMOR_APPLICATIONS_INSTALL_DIR})
