set(COMPONENT_SRCS
       ubirch-protocol-c8y.c
        )
set(COMPONENT_ADD_INCLUDEDIRS ".")

set(COMPONENT_PRIV_REQUIRES
        nvs_flash
        json
        esp_http_client
        )
set(COMPONENT_REQUIRES
        ubirch-esp32-storage
        ubirch-esp32-networking
        ubirch-protocol
        )
register_component()