add_hermes_library(LLVHDemangle
  ItaniumDemangle.cpp
  MicrosoftDemangle.cpp
  MicrosoftDemangleNodes.cpp
)

set_target_properties(LLVHDemangle PROPERTIES FOLDER "External/llvh")
set_target_properties(LLVHDemangle_obj PROPERTIES FOLDER "External/llvh")
