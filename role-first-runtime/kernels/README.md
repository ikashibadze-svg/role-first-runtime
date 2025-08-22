# kernels/

Templates your engineer tunes. Start with three Triton kernels and two CUTLASS configs.

- `triton/` : gather, segmented-reduce, top-k (with `num_warps`, `num_stages`, `BLOCK` tiles)
- `cutlass/`: reformat/cast epilogues, kv-move helpers
