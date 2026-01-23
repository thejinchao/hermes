add_hermes_library(gtest_main
  TestMain.cpp

  LINK_LIBS
  gtest

  LINK_OBJLIBS
  LLVHSupport # Depends on llvh::cl
  )

 set_target_properties(gtest_main PROPERTIES FOLDER "External/llvh")
 set_target_properties(gtest_main_obj PROPERTIES FOLDER "External/llvh")
