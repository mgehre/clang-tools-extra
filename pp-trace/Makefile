##===- extra/pp-trace/Makefile --------------------------*- Makefile -*---===##
#
#                     The LLVM Compiler Infrastructure
#
# This file is distributed under the University of Illinois Open Source
# License. See LICENSE.TXT for details.
#
##===---------------------------------------------------------------------===##

CLANG_LEVEL := ../../..

TOOLNAME = pp-trace

# No plugins, optimize startup time.
TOOL_NO_EXPORTS = 1

LINK_COMPONENTS := mcparser bitreader support mc option TransformUtils
USEDLIBS = clangFrontend.a clangSerialization.a clangDriver.a \
           clangTooling.a clangParse.a clangSema.a clangAnalysis.a \
           clangEdit.a clangAST.a clangLex.a clangBasic.a

include $(CLANG_LEVEL)/Makefile
