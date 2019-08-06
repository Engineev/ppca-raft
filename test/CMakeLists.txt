add_executable(${PROJECT_NAME}-test test.cpp)

target_compile_features(${PROJECT_NAME}-test PRIVATE cxx_std_14)
#target_compile_options(${PROJECT_NAME}-test PRIVATE -O2 -Wall)