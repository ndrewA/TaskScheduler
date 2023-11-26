add_library(TaskScheduler STATIC)

target_compile_features(TaskScheduler PUBLIC cxx_std_20)

target_sources(TaskScheduler PRIVATE source.cpp)
target_include_directories(TaskScheduler PUBLIC ${CMAKE_SOURCE_DIR}/include)
