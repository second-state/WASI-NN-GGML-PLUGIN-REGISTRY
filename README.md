# WasmEdge WASI-NN GGML PLUGIN REGISTRY

The llama.cpp project is in active development. Hence, we have to bump the version frequently.
To avoid the previous assets being removed or hard to find, we provide this repository for those who want to downgrade or get the specific version of the plugin.

## Structure

```
WasmEdge version
|- llama.cpp version
   |- xxx.tar.gz
```

E.g.

```
0.13.5
├── b1444
│   ├── WasmEdge-plugin-wasi_nn-ggml-0.13.5-darwin_arm64.tar.gz
│   ├── WasmEdge-plugin-wasi_nn-ggml-0.13.5-darwin_x86_64.tar.gz
│   ├── WasmEdge-plugin-wasi_nn-ggml-0.13.5-manylinux2014_aarch64.tar.gz
│   ├── WasmEdge-plugin-wasi_nn-ggml-0.13.5-manylinux2014_x86_64.tar.gz
│   ├── WasmEdge-plugin-wasi_nn-ggml-0.13.5-ubuntu20.04_aarch64.tar.gz
│   ├── WasmEdge-plugin-wasi_nn-ggml-0.13.5-ubuntu20.04_x86_64.tar.gz
│   ├── WasmEdge-plugin-wasi_nn-ggml-cuda-0.13.5-ubuntu20.04_aarch64.tar.gz
│   └── WasmEdge-plugin-wasi_nn-ggml-cuda-0.13.5-ubuntu20.04_x86_64.tar.gz
└── b1656
    ├── WasmEdge-plugin-wasi_nn-ggml-0.13.5-darwin_arm64.tar.gz
    ├── WasmEdge-plugin-wasi_nn-ggml-0.13.5-manylinux2014_aarch64.tar.gz
    ├── WasmEdge-plugin-wasi_nn-ggml-0.13.5-manylinux2014_x86_64.tar.gz
    ├── WasmEdge-plugin-wasi_nn-ggml-0.13.5-ubuntu20.04_aarch64.tar.gz
    ├── WasmEdge-plugin-wasi_nn-ggml-0.13.5-ubuntu20.04_x86_64.tar.gz
    ├── WasmEdge-plugin-wasi_nn-ggml-blas-0.13.5-ubuntu20.04_aarch64.tar.gz
    ├── WasmEdge-plugin-wasi_nn-ggml-blas-0.13.5-ubuntu20.04_x86_64.tar.gz
    ├── WasmEdge-plugin-wasi_nn-ggml-cuda-0.13.5-ubuntu20.04_aarch64.tar.gz
    └── WasmEdge-plugin-wasi_nn-ggml-cuda-0.13.5-ubuntu20.04_x86_64.tar.gz
```
