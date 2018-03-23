set(scripts scripts/amorTools.xml
            scripts/sensors.xml)

yarp_install(FILES ${scripts}
             DESTINATION ${AMOR_APPLICATIONS_INSTALL_DIR})
