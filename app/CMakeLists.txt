set(SOURCES 
main.cpp
)

add_executable(app ${SOURCES})
set_project_warnings(app)

target_link_libraries(app PRIVATE CONAN_PKG::fmt CONAN_PKG::spdlog)