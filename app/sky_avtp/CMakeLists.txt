aux_source_directory(. DIR_APP_SRC)

include_directories(
)

add_library(sky_avtp ${DIR_APP_SRC})

target_link_libraries(sky_avtp)

