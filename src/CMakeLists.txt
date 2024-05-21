cmake_minimum_required(VERSION 3.16)

add_library(installer_fomod_csharp SHARED)
mo2_configure_plugin(installer_fomod_csharp WARNINGS OFF CLI ON)
mo2_install_target(installer_fomod_csharp)

set_target_properties(installer_fomod_csharp PROPERTIES CXX_STANDARD 20)
