idf_component_register(SRCS "uartmidi.c"
                       INCLUDE_DIRS "include"
                       REQUIRES driver
                       PRIV_REQUIRES nvs_flash console)
