idf_component_register(
  SRCS "rp2040.c" "rp2040bl.c"
  INCLUDE_DIRS include
	REQUIRES esp_driver_gpio esp_driver_i2c esp_driver_uart
)
