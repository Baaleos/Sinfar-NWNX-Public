file(GLOB source_files "*.cpp" "*.h")
add_library(ee_compat SHARED ${common_source_files} ${source_files})
target_link_libraries(ee_compat)
