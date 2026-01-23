add_hermes_executable(llvh-tblgen
  TableGen.cpp
  Example.cpp

  LINK_LIBS LLVHSupport_obj LLVHTableGen_obj
  )

set_target_properties(llvh-tblgen PROPERTIES FOLDER "External/llvh")
