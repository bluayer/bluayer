Welcome to my page!

I'm **Jungwoo Song**, solutions architect from **Seoul, Korea**.

### DRA Driver for NVIDIA GPUs

- `2026.11` Added a claim-scoped local IPC directory, enabling cross-Pod CUDA IPC without hostIPC or hostPath ([#1391](https://github.com/kubernetes-sigs/dra-driver-nvidia-gpu/pull/1391))

### LMCache

- (In progress) `2026.10` Adding a POSIX fd delivery channel so MP mode can register VMM KV pools on GPUs without IMEX ([#5867](https://github.com/LMCache/LMCache/pull/5867))
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

#### GLIDE RDMA

- (In progress) `2026.11` Registering CUDA tensors such as `torch.Tensor` and CuPy arrays in Python glide-sync, so the server reads and writes GPU memory directly ([valkey-glide#7812](https://github.com/valkey-io/valkey-glide/pull/7812))
- (In progress) `2026.11` Adding fabric groups and shared regions, so clients register memory once and run concurrent transfers through it ([valkey-glide#7587](https://github.com/valkey-io/valkey-glide/pull/7587))
- `2026.11` Registered CUDA device memory for RDMA transfers, so GPU data moves to and from Valkey without a copy through a host buffer ([valkey-glide#7609](https://github.com/valkey-io/valkey-glide/pull/7609))

### NIXL

- (In progress) `2026.11` Adding a Valkey storage plugin that moves NIXL buffers to and from Valkey over GLIDE RDMA, without sending the payload over RESP ([#2577](https://github.com/ai-dynamo/nixl/pull/2577))

### KServe

- `2026.02` Parallelized S3 file downloads, making model downloads about 2x faster ([#5102](https://github.com/kserve/kserve/pull/5102))

### Karmada

- `2026.08` Built seven agent skills for Karmada users through the LFX Mentorship program ([community#216](https://github.com/karmada-io/community/pull/216))

## How to reach me ...

*bluayer@gmail.com*
