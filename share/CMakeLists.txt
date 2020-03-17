yarp_install(FILES applications/ymanager.ini
                   applications/amorBase.xml
                   applications/amorSimBase.xml
                   applications/amorTools.xml
                   applications/sensors.xml
             DESTINATION ${AMOR-CONFIGURATION-FILES_APPLICATIONS_INSTALL_DIR})

yarp_install(DIRECTORY yarpmotorgui
                       ../doc/fig
             DESTINATION ${AMOR-CONFIGURATION-FILES_DATA_INSTALL_DIR})

yarp_install(DIRECTORY contexts/kinematics
             DESTINATION ${AMOR-CONFIGURATION-FILES_CONTEXTS_INSTALL_DIR})
