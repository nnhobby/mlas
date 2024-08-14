# About MLAS
MLAS is a compute library containing processor optimized GEMM kernels and platform specific threading code.

## version

newer than onnxruntime: v1.19.0
commit hash: b92908e19758d2a8eb1dc957b7839c72c5fdc135

## code modifications

1. *mlasi.h* add <array> and <cstring> to support *std::array* and *memset*
2. *platform.cpp* add <unistd.h> to support *syscall*
3. *q4_dq.cpp* comment *ORT_ENFORCE* and *ORT_THROW*
4. add *CMakeLists.txt*
5. support *openmp*
