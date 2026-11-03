# Model-Optimizer Changelog — 2026-11

> Auto-generated from [NVIDIA/Model-Optimizer](https://github.com/NVIDIA/Model-Optimizer) merged PRs.

> Rows marked with color emoji contain **high-priority** tags:

> 🟡 `eval`  🔵 `vllm`  🟣 `vlm`  🟠 `onnx`

| Focus | Date | Commit | PR | Author | Tags | Description |
|:-----:|------|--------|-------|--------|------|-------------|
| 🟠 | **2026-11-03** | **[8d19f74d](https://github.com/NVIDIA/Model-Optimizer/commit/8d19f74d1321f0686b99ca994d362ff706791070)** | **[#3013](https://github.com/NVIDIA/Model-Optimizer/pull/3013)** | **[@Tracy-123-dev](https://github.com/Tracy-123-dev)** | `diffusers` `docs` `example` `export` `infra` `onnx` `quantization` `tests` `torch` | **Fix ONNX export for initializers larger than 2 GiB** |
|  | 2026-11-03 | [4319255b](https://github.com/NVIDIA/Model-Optimizer/commit/4319255bd2f52285c7fef856d5449e7be6ae9681) | [#3177](https://github.com/NVIDIA/Model-Optimizer/pull/3177) | [@kevalmorabia97](https://github.com/kevalmorabia97) | `core` `tests` `torch` | Make the megatron tests run on 4-GPU nodes |
|  | 2026-11-03 | [db6700df](https://github.com/NVIDIA/Model-Optimizer/commit/db6700df2c5c037144299b0befb8af6d387fe474) | [#3125](https://github.com/NVIDIA/Model-Optimizer/pull/3125) | [@kevalmorabia97](https://github.com/kevalmorabia97) | `core` `tests` `torch` | Test Nemotron-H and Qwen3.5-VL bridge export with full NVFP4 |
|  | 2026-11-03 | [7d442467](https://github.com/NVIDIA/Model-Optimizer/commit/7d442467504cdae155812baf15242628d96971b5) | [#2780](https://github.com/NVIDIA/Model-Optimizer/pull/2780) | [@shengliangxu](https://github.com/shengliangxu) | `core` `docs` `infra` `tests` `torch` | \[OMNIML-6060\] Load an expert-parallel plan through load_pretrained, and apply the model spec when deciding and loading it |
|  | 2026-11-03 | [472ecb39](https://github.com/NVIDIA/Model-Optimizer/commit/472ecb39ad498a6b0d818583d5b1dc483a708abf) | [#3179](https://github.com/NVIDIA/Model-Optimizer/pull/3179) | [@yingguo-trt](https://github.com/yingguo-trt) | `infra` `quantization` `tests` `torch` | \[NVBug 7035880\] Apply the calibrated bias in NVFP4 affine KV fake quantization |
| 🔵 | **2026-11-02** | **[509acae9](https://github.com/NVIDIA/Model-Optimizer/commit/509acae921bad5bcb6a1fb96a8cc5ceb4fb3f6b2)** | **[#3098](https://github.com/NVIDIA/Model-Optimizer/pull/3098)** | **[@kinjalpatel27](https://github.com/kinjalpatel27)** | `deploy` `example` `vllm` | **Document vLLM fakequant layer and backend support** |
|  | 2026-11-01 | [51645db6](https://github.com/NVIDIA/Model-Optimizer/commit/51645db66dc363b0f8df3f72b1d4373a27ae7273) | [#3140](https://github.com/NVIDIA/Model-Optimizer/pull/3140) | [@shengliangxu](https://github.com/shengliangxu) | `core` `tests` `torch` | \[OMNIML-6054\] \[1/2\] Move fsdp2_wrap out of distributed.py into fsdp2_utils |
|  | 2026-11-01 | [d48a5450](https://github.com/NVIDIA/Model-Optimizer/commit/d48a5450d70e7ec4d9ea22bc6ce4d403fef37a12) | [#1986](https://github.com/NVIDIA/Model-Optimizer/pull/1986) | [@ChenhanYu](https://github.com/ChenhanYu) | `infra` | Track launcher jobs in MLflow and prepare required assets |

---
**Total: 8 PRs** | **Highlighted: 2**
