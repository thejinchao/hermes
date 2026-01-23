# Copyright (c) Meta Platforms, Inc. and affiliates.
#
# This source code is licensed under the MIT license found in the
# LICENSE file in the root directory of this source tree.

add_hermes_library(hermesAST2JS
    AST2JS.cpp
    LINK_OBJLIBS hermesAST
)

set_target_properties(hermesAST2JS PROPERTIES FOLDER "Lib/AST2JS")
set_target_properties(hermesAST2JS_obj PROPERTIES FOLDER "Lib/AST2JS")
