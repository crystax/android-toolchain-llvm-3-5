set(LLVM_LINK_COMPONENTS
  asmparser
  bitreader
  bitwriter
  codegen
  instrumentation
  ipo
  linker
  selectiondag
  )

add_llvm_tool(ndk-link
  AndroidBitcodeLinker.cpp
  ndk-link.cpp
  )
