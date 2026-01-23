add_hermes_tool(FileCheck
  FileCheck.cpp
  )

target_link_libraries(FileCheck PRIVATE LLVHSupport)


set_target_properties(FileCheck PROPERTIES FOLDER "External/llvh")
