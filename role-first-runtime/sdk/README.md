# sdk/ (Interposer runtime)

**Plain English:** This is the small plugin that sits between the app and the GPU software.  
It reads `policies/policy.yaml` and chooses better schedules (tiling, pipelining, streams).

**What the engineer will do here**
- Implement an **LD_PRELOAD** library (CUDA/HIP) that wraps kernel launches.
- Read the policy YAML and set: stream priority, CUDA Graph capture, tile sizes/stages.
- Emit an **evidence JSON** per kernel: R, M, ΔH, D, counters, and speedup.

**Deliverables**
- `librolefirst.so` (Linux) or `rolefirst.dll` (Windows).
- A tiny CLI: `rolefirst --dry-run`, `rolefirst --profile`.
