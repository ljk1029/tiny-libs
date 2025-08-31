# 设置版本 
cmake_minimum_required(VERSION 3.4.1) 
project(common)

# 默认的输出路径
set(DEFAULT_BIN_OUTPUT_PATH "${CMAKE_SOURCE_DIR}/../bin")

# 从命令行参数设置输出路径，如果没有提供参数，则使用默认值
# cmake .. -DBUILD_PATH=/path/bin
if(DEFINED BUILD_PATH)
    set(BIN_OUTPUT_PATH ${BUILD_PATH})
else()
    set(BIN_OUTPUT_PATH ${DEFAULT_BIN_OUTPUT_PATH})
endif()

add_subdirectory(json/base64)
add_subdirectory(json/cjson)
#add_subdirectory(json/protobuf)
add_subdirectory(sql/sqlite3)
add_subdirectory(logging/spdlog)
add_subdirectory(logging/zlog)
add_subdirectory(logging/gtest)


# 与1.0.27版本的生成物重名了
#add_subdirectory(libusb) 
add_subdirectory(usb/libusb-1.0.27)
add_subdirectory(usb/hidapi)








