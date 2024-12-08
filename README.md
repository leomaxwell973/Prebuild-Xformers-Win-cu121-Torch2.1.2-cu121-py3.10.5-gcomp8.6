# Prebuild-Xformers 0.0.24+cu121 - Win - Torch2.1.2+cu121 - py3.10.5 - GPU/Torch Compute Arch 8.6
Prebuild Xformers built on Win with cuda 12.1 Torch 2.1.2+cu121 python 3.10.5 gpu compute arch  8.6 Prebuilt (unpacked)

Hoping that for anyone matching it works just dropping in if they need it dueto build difficulties or time restraints. 
Has full Flash-Attn enabled etc.

```
xFormers 0.0.24+042abc8a.d20241208
memory_efficient_attention.cutlassF:               available
memory_efficient_attention.cutlassB:               available
memory_efficient_attention.decoderF:               available
memory_efficient_attention.flshattF@v2.3.6:        available
memory_efficient_attention.flshattB@v2.3.6:        available
memory_efficient_attention.smallkF:                available
memory_efficient_attention.smallkB:                available
memory_efficient_attention.tritonflashattF:        unavailable
memory_efficient_attention.tritonflashattB:        unavailable
memory_efficient_attention.triton_splitKF:         available
indexing.scaled_index_addF:                        available
indexing.scaled_index_addB:                        available
indexing.index_select:                             available
swiglu.dual_gemm_silu:                             available
swiglu.gemm_fused_operand_sum:                     available
swiglu.fused.p.cpp:                                available
is_triton_available:                               True
pytorch.version:                                   2.1.2+cu121
pytorch.cuda:                                      available
gpu.compute_capability:                            8.6
gpu.name:                                          NVIDIA GeForce RTX 3060
dcgm_profiler:                                     unavailable
build.info:                                        available
build.cuda_version:                                1201
build.python_version:                              3.10.5
build.torch_version:                               2.1.2+cu121
build.env.TORCH_CUDA_ARCH_LIST:                    8.6
build.env.XFORMERS_BUILD_TYPE:                     None
build.env.XFORMERS_ENABLE_DEBUG_ASSERTIONS:        None
build.env.NVCC_FLAGS:                              None
build.env.XFORMERS_PACKAGE_FROM:                   None
build.nvcc_version:                                12.1.66
source.privacy:                                    open source
```
