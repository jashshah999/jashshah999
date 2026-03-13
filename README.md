## Open Source Contributions

17 PRs merged across 7 repos.

[GTSAM](https://github.com/borglab/gtsam) | [LeRobot](https://github.com/huggingface/lerobot) | [Rerun](https://github.com/rerun-io/rerun) | [PyTorch RL](https://github.com/pytorch/rl) | [Transformers](https://github.com/huggingface/transformers) | [Accelerate](https://github.com/huggingface/accelerate) | [RSL_RL](https://github.com/leggedrobotics/rsl_rl)

---

<details open>
<summary><b>GTSAM</b> — 5 PRs</summary>

| PR | Description |
|---|---|
| [#2456](https://github.com/borglab/gtsam/pull/2456) | Fix `enforceConsistency_` in BatchFixedLagSmoother -- first-estimates Jacobian logic was silently broken |
| [#2463](https://github.com/borglab/gtsam/pull/2463) | Fix incorrect key in cheirality error message for PPP/PPPC factors |
| [#2464](https://github.com/borglab/gtsam/pull/2464) | Fix `tMin_` reset when an iteration has zero duration |
| [#2465](https://github.com/borglab/gtsam/pull/2465) | Reject negative sigma values in noise model constructors |
| [#2467](https://github.com/borglab/gtsam/pull/2467) | Fix `LinearContainerFactor::rekey()` segfault without linearization point |

</details>

<details>
<summary><b>HuggingFace LeRobot</b> — 3 PRs</summary>

| PR | Description |
|---|---|
| [#2486](https://github.com/huggingface/lerobot/pull/2486) | Enable `torch.compile` for DiffusionPolicy -- inference speedup for real-time robot control |
| [#3016](https://github.com/huggingface/lerobot/pull/3016) | Replace assertions with proper exceptions in video frame decoding |
| [#3017](https://github.com/huggingface/lerobot/pull/3017) | Fix missing config file in pip installs causing AttributeError crash |

</details>

<details>
<summary><b>Rerun</b> — 3 PRs</summary>

| PR | Description |
|---|---|
| [#12672](https://github.com/rerun-io/rerun/pull/12672) | Fix incorrect byte unit conversion values in render benchmark |
| [#12673](https://github.com/rerun-io/rerun/pull/12673) | Reuse precomputed timelines dict in `send_columns` instead of re-iterating |
| [#12674](https://github.com/rerun-io/rerun/pull/12674) | Fix wrong variable in error message for extra args in `log()` |

</details>

<details>
<summary><b>RSL_RL</b> — 2 PRs</summary>

| PR | Description |
|---|---|
| [#180](https://github.com/leggedrobotics/rsl_rl/pull/180) | Fix missing raise, wrong RND broadcast index, and variable typo |
| [#181](https://github.com/leggedrobotics/rsl_rl/pull/181) | Fix mutable default arguments and replace assertions with proper exceptions |

</details>

<details>
<summary><b>PyTorch RL</b> — 1 PR</summary>

| PR | Description |
|---|---|
| [#3530](https://github.com/pytorch/rl/pull/3530) | Fix missing raise, incorrect `__torch_function__` return, and off-by-one in RayCollector |

</details>

<details>
<summary><b>HuggingFace Transformers</b> — 1 PR</summary>

| PR | Description |
|---|---|
| [#44287](https://github.com/huggingface/transformers/pull/44287) | Fix mutable default arguments and resource leaks |

</details>

<details>
<summary><b>HuggingFace Accelerate</b> — 1 PR</summary>

| PR | Description |
|---|---|
| [#3944](https://github.com/huggingface/accelerate/pull/3944) | Fix mutable default in Megatron init and IndexError on empty ModuleList |

</details>
