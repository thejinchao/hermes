# Copyright (c) Meta Platforms, Inc. and affiliates.
#
# This source code is licensed under the MIT license found in the
# LICENSE file in the root directory of this source tree.

add_hermes_library(hermesSourceMap
    c-api.cpp
    SourceMap.cpp
    SourceMapGenerator.cpp
    SourceMapParser.cpp
    SourceMapTranslator.cpp
    LINK_OBJLIBS hermesParser
)

set_target_properties(hermesSourceMap PROPERTIES FOLDER "Lib/SourceMap")
set_target_properties(hermesSourceMap_obj PROPERTIES FOLDER "Lib/SourceMap")
