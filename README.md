# WasmEdge WASI-NN GGML PLUGIN REGISTRY

The llama.cpp project is in active development. Hence, we have to bump the version frequently.
To avoid the previous assets being removed or hard to find, we provide this repository for those who want to downgrade or get the specific version of the plugin.

## Structure

Please check the release pages for the assets

```
0.13.5
|- b3613
|- no longer updated, if you need a new version of the ggml plugin, please use 0.14.1
0.14.0
|- b3613
|- no longer updated, if you need a new version of the ggml plugin, please use 0.14.1
0.14.1
|- b3651
|- *b4067 (DO NOT USE, cannot run embedding)
|- *b4242 (DO NOT USE, fixed the embedding issue, but failed the context lifecycle)
|- b4273 (fixed the context lifecycle issue)
|- b4381 (Support Qwen-2-VL)
|- b4419 (Support DeepSeekV3)
|- b4466 (Reduce Qwen2VL image embedding time)
|- b4623
```
