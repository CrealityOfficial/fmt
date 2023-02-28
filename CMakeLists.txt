if(CC_INSTALL_FMT)
	__install_directory_specif(${CMAKE_CURRENT_SOURCE_DIR}/ fmt)
endif()

add_library(fmt INTERFACE)
set_property(TARGET fmt PROPERTY INTERFACE_INCLUDE_DIRECTORIES ${CMAKE_CURRENT_SOURCE_DIR})