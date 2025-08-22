# Proof of Value (PoV) – One Pager

**Customer:** <Name>   |   **Workload:** <LLM/RAG/Recsys>   |   **Dates:** <start–end>

## 1) Result summary
- Throughput uplift: **< +XX% >**
- GPUs saved (if applicable): **< N × (1 − 1/u) >**
- Latency tail (p95) change: **< −YY% >**

## 2) Before vs After (charts)
- tokens/s or GB/s
- L2 hit-rate, DRAM BW, memory stalls

## 3) What changed (auditable)
- R (RoleFit) ↑ : <why this kernel matched hardware better>
- M (Resonance) ↑ : <hot data co-located>
- ΔH (Entropy↓) ↑ : <tiling/pipelining regularized access>
- D (Dissonance) ↓ : <avoided conflicts>

## 4) Commercial
- Pricing: <per GPU/month> or <X% of savings for Y months>
- Next steps: <production rollout plan>
