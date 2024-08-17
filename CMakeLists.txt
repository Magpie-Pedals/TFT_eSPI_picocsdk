
add_library(LCD TFT_eSPI.cpp)
target_link_libraries(LCD PRIVATE
    pico_stdlib,
    hardware_spi)