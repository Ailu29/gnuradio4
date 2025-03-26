install(
    FILES ImChart.hpp
          SchmittTrigger.hpp
    DESTINATION ${GR_INCLUDE_DIR}/gnuradio-4.0/algorithm)

add_subdirectory(dataset)
add_subdirectory(filter)
add_subdirectory(fourier)