idf_component_register(SRCS "cmd_router.c"
                    INCLUDE_DIRS .
                    REQUIRES console spi_flash nvs_flash esp_wifi driver)
