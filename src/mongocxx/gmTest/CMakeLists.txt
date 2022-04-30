include_directories(
    ${GMSSL_SOURCE_DIR}/include
)

set(SOURCE_FILES "gmTest.cpp")

add_executable (gmTest ${SOURCE_FILES})

target_link_libraries(gmTest gmssl)