add_llvm_library(LLVMHexagonDesc
  HexagonAsmBackend.cpp
  HexagonELFObjectWriter.cpp
  HexagonInstPrinter.cpp
  HexagonMCAsmInfo.cpp
  HexagonMCChecker.cpp
  HexagonMCCodeEmitter.cpp
  HexagonMCCompound.cpp
  HexagonMCDuplexInfo.cpp
  HexagonMCELFStreamer.cpp
  HexagonMCExpr.cpp
  HexagonMCInstrInfo.cpp
  HexagonMCShuffler.cpp
  HexagonMCTargetDesc.cpp
  HexagonShuffler.cpp
  )

add_dependencies(LLVMHexagonDesc HexagonCommonTableGen)
