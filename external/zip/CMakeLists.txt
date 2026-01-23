set(SRC src/zip.c)
add_hermes_library(zip ${SRC})

set_target_properties(zip PROPERTIES FOLDER "External/zip")
set_target_properties(zip_obj PROPERTIES FOLDER "External/zip")
