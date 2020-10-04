# SPDX-License-Identifier: Apache-2.0

if(CONFIG_ZPP)
zephyr_interface_library_named(ZPP)
zephyr_include_directories(ZPP INTERFACE include)
endif()
