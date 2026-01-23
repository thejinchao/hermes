add_hermes_library(LLVHTableGen
  Error.cpp
  JSONBackend.cpp
  Main.cpp
  Record.cpp
  SetTheory.cpp
  StringMatcher.cpp
  TableGenBackend.cpp
  TGLexer.cpp
  TGParser.cpp
  )

set_target_properties(LLVHTableGen PROPERTIES FOLDER "External/llvh")
set_target_properties(LLVHTableGen_obj PROPERTIES FOLDER "External/llvh")
