# eos-debian9
eos build shell script on debian 9 Stretch

clang-4.0 install from llvm.org source.

cmake clang-4.0 must compile with -DLLVM_ENABLE_RTTI=1

make, install clang

export LLVM_DIR=/path/llvm-4.0

cd /path/to/eos to run eos build.
