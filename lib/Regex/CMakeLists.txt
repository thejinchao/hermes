# Copyright (c) Meta Platforms, Inc. and affiliates.
#
# This source code is licensed under the MIT license found in the
# LICENSE file in the root directory of this source tree.

set(source_files
  RegexParser.cpp
  RegexSerialization.cpp
  Executor.cpp
)

add_hermes_library(hermesRegex
    ${source_files}
    LINK_OBJLIBS hermesPlatformUnicode
)



set_target_properties(hermesRegex PROPERTIES FOLDER "Lib/Regex")
set_target_properties(hermesRegex_obj PROPERTIES FOLDER "Lib/Regex")
