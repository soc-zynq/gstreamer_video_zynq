# Create a library called "gstreamer_video_zynq"
add_library(gstreamer_video_zynq_lib gstreamer_video_zynq.cpp)

# Specify include directories for the library
target_include_directories(gstreamer_video_zynq_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../../include)
