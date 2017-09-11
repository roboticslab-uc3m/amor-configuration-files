add_subdirectory(kinematics)
add_subdirectory(amorTools)

yarp_install(FILES ymanager.ini
             DESTINATION ${AMOR_APPLICATIONS_INSTALL_DIR})

yarp_install(FILES yarpmotorgui/amor-yarpmotorgui.ini
             DESTINATION ${AMOR_APPLICATIONS_INSTALL_DIR})

yarp_install(FILES ${CMAKE_SOURCE_DIR}/doc/fig/RL_logo_64x64.png
             DESTINATION ${AMOR_APPLICATIONS_INSTALL_DIR})
