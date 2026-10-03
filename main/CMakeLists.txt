 idf_component_register(
       SRCS "main.c" "i2s.c"
       INCLUDE_DIRS "."
       REQUIRES esp_driver_i2s
   )