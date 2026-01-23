add_hermes_tool(not
  not.cpp
  )

target_link_libraries(not PRIVATE LLVHSupport)

set_target_properties(not PROPERTIES FOLDER "External/llvh")
