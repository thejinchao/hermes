add_hermes_library(llvh-gtest_main
  TestMain.cpp

  LINK_LIBS
  llvh-gtest

  LINK_OBJLIBS
  LLVHSupport # Depends on llvh::cl
  )

 set_target_properties(llvh-gtest_main PROPERTIES FOLDER "External/llvh")
 set_target_properties(llvh-gtest_main_obj PROPERTIES FOLDER "External/llvh")
