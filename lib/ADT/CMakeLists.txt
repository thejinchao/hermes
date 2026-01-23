# Copyright (c) Meta Platforms, Inc. and affiliates.
#
# This source code is licensed under the MIT license found in the
# LICENSE file in the root directory of this source tree.

add_hermes_library(hermesADT
  CompactArray.cpp
  LINK_OBJLIBS hermesSupport
)

set_target_properties(hermesADT PROPERTIES FOLDER "Lib/ADT")
set_target_properties(hermesADT_obj PROPERTIES FOLDER "Lib/ADT")
