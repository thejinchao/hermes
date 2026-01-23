# Copyright (c) Meta Platforms, Inc. and affiliates.
#
# This source code is licensed under the MIT license found in the
# LICENSE file in the root directory of this source tree.

set(source_files
  InstDecode.cpp
  InstDecode2.cpp
)

add_hermes_library(hermesInst ${source_files}
  LINK_OBJLIBS
  hermesSupport
  hermesFrontEndDefs
)

set_target_properties(hermesInst PROPERTIES FOLDER "Lib/Inst")
set_target_properties(hermesInst_obj PROPERTIES FOLDER "Lib/Inst")
