Welcome to my page!

I'm **Jungwoo Song**, solutions architect from **Seoul, Korea**.

## I'm currently working on ...

Contribute to LMCache, Valkey, KServe, Karmada

### Recent PRs I'm enjoying
  
- `2026.10` Growing padded full attention blocks in vLLM to fill the unified KV page, adding about 16% KV cache capacity for hybrid models like Gemma-4 and Qwen3.6 ([vllm#63347](https://github.com/vllm-project/vllm/pull/63347))
- `2026.10` Adding a POSIX fd delivery channel so LMCache MP mode can register VMM KV pools on GPUs without IMEX ([LMCache#5867](https://github.com/LMCache/LMCache/pull/5867))
- `2026.08` Adding a claim-scoped local IPC directory to the NVIDIA GPU DRA driver, enabling cross-Pod CUDA IPC without hostIPC or hostPath ([dra-driver-nvidia-gpu#1391](https://github.com/kubernetes-sigs/dra-driver-nvidia-gpu/pull/1391))

### LMCache

- `2026.10` Fixed KV registration for hybrid models with padded KV pools under CUDA IPC ([#5693](https://github.com/LMCache/LMCache/pull/5693), [#5855](https://github.com/LMCache/LMCache/pull/5855))
- `2026.10` Supported KV events under MultiConnector for P/D disaggregation ([#5524](https://github.com/LMCache/LMCache/pull/5524))
- `2026.08` Made hostIPC optional in the LMCache operator, part of the [2026 Q3 roadmap](https://github.com/LMCache/LMCache/issues/4025) to remove the hostIPC and privileged mode requirements ([#4399](https://github.com/LMCache/LMCache/pull/4399))
- `2026.07` Attached the SageMaker HyperPod daemon's shared memory read-only, so an LMCache pod restart no longer wipes the node-wide cache ([#4181](https://github.com/LMCache/LMCache/pull/4181))
- `2026.07` Added a SageMaker HyperPod L2 adapter for MP mode ([#4138](https://github.com/LMCache/LMCache/pull/4138))
- `2026.03` Supported numbered databases in the Valkey connector, including Valkey 9.0 cluster mode ([#2307](https://github.com/LMCache/LMCache/pull/2307))
- `2025.10` Contributed a Valkey connector with pipelining, achieving at least 20% RTT improvement over the existing Redis connector ([#1743](https://github.com/LMCache/LMCache/pull/1743))

### Valkey

- `2026.09` Guarded HNSW prefetches against empty neighbor lists in valkey-search ([valkey-search#1320](https://github.com/valkey-io/valkey-search/pull/1320))
- `2025.03` Documented the valkey-benchmark `--rfr` option ([valkey-doc#254](https://github.com/valkey-io/valkey-doc/pull/254))
- `2024.12` Enabled reads from replicas in valkey-benchmark for more accurate cluster-mode testing ([valkey#1392](https://github.com/valkey-io/valkey/pull/1392))

### KServe

- `2026.02` Parallelized S3 file downloads, making model downloads about 2x faster ([#5102](https://github.com/kserve/kserve/pull/5102))

### Karmada

- `2026.08` Built seven agent skills for Karmada users through the LFX Mentorship program ([community#216](https://github.com/karmada-io/community/pull/216))

## How to reach me ...

*bluayer@gmail.com*
