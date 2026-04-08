add_hermes_tool(FileCheck
  FileCheck.cpp
FOLDER_PROPERTY
  "Tools"
  )

target_link_libraries(FileCheck PRIVATE LLVHSupport)
