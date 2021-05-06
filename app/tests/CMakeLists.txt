set(SOURCES 
main.cpp
)

add_executable(appTest ${SOURCES})

target_link_libraries(appTest PRIVATE CONAN_PKG::gtest)