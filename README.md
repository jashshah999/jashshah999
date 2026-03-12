## Open Source Contributions

13 PRs merged across 7 repos.

### [HuggingFace LeRobot](https://github.com/huggingface/lerobot)

| PR | Description |
|---|---|
| [#2486](https://github.com/huggingface/lerobot/pull/2486) | Enable `torch.compile` for DiffusionPolicy -- inference speedup for real-time robot control |
| [#3016](https://github.com/huggingface/lerobot/pull/3016) | Replace assertions with proper exceptions in video frame decoding |
| [#3017](https://github.com/huggingface/lerobot/pull/3017) | Fix missing config file in pip installs causing AttributeError crash |

### [PyTorch RL](https://github.com/pytorch/rl)

| PR | Description |
|---|---|
| [#3530](https://github.com/pytorch/rl/pull/3530) | Fix missing raise, incorrect `__torch_function__` return, and off-by-one in RayCollector |

### [HuggingFace Transformers](https://github.com/huggingface/transformers)

| PR | Description |
|---|---|
| [#44287](https://github.com/huggingface/transformers/pull/44287) | Fix mutable default arguments and resource leaks |

### [HuggingFace Accelerate](https://github.com/huggingface/accelerate)

| PR | Description |
|---|---|
| [#3944](https://github.com/huggingface/accelerate/pull/3944) | Fix mutable default in Megatron init and IndexError on empty ModuleList |

### [GTSAM](https://github.com/borglab/gtsam)

| PR | Description |
|---|---|
| [#2456](https://github.com/borglab/gtsam/pull/2456) | Fix `enforceConsistency_` in BatchFixedLagSmoother -- first-estimates Jacobian logic was silently broken |
| [#2465](https://github.com/borglab/gtsam/pull/2465) | Reject negative sigma values in noise model constructors |

### [Rerun](https://github.com/rerun-io/rerun)

| PR | Description |
|---|---|
| [#12672](https://github.com/rerun-io/rerun/pull/12672) | Fix incorrect byte unit conversion values in render benchmark |
| [#12673](https://github.com/rerun-io/rerun/pull/12673) | Reuse precomputed timelines dict in `send_columns` instead of re-iterating |
| [#12674](https://github.com/rerun-io/rerun/pull/12674) | Fix wrong variable in error message for extra args in `log()` |

### [RSL_RL](https://github.com/leggedrobotics/rsl_rl)

| PR | Description |
|---|---|
| [#180](https://github.com/leggedrobotics/rsl_rl/pull/180) | Fix missing raise, wrong RND broadcast index, and variable typo |
| [#181](https://github.com/leggedrobotics/rsl_rl/pull/181) | Fix mutable default arguments and replace assertions with proper exceptions |
