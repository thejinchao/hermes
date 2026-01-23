# Copyright (c) Meta Platforms, Inc. and affiliates.
#
# This source code is licensed under the MIT license found in the
# LICENSE file in the root directory of this source tree.

add_hermes_library(hermesPlatform
        Logging.cpp
)

add_subdirectory(Intl)
add_subdirectory(Unicode)

set_target_properties(hermesPlatform PROPERTIES FOLDER "Lib/Platform")
set_target_properties(hermesPlatform_obj PROPERTIES FOLDER "Lib/Platform")
