set(scripts scripts/amorTools.xml
            scripts/sensor_reader.py)

yarp_install(FILES ${scripts}
             DESTINATION ${AMOR_APPLICATIONS_INSTALL_DIR})
