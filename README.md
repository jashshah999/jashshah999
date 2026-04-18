Hi, I'm Jash.

[![Email](https://img.shields.io/badge/Email-jashshah.999%40gmail.com-red?style=flat-square&logo=gmail&logoColor=white)](mailto:jashshah.999@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Jash%20Shah-blue?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jash-shah-999-new/)

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=jashshah999&show_icons=true&theme=dark&count_private=true&show=prs_merged&include_all_commits=true)

---

## Open Source Contributions

24 PRs merged across 12 repos.

[GTSAM](https://github.com/borglab/gtsam) | [LeRobot](https://github.com/huggingface/lerobot) | [PyTorch RL](https://github.com/pytorch/rl) | [Rerun](https://github.com/rerun-io/rerun) | [RSL_RL](https://github.com/leggedrobotics/rsl_rl) | [Transformers](https://github.com/huggingface/transformers) | [Accelerate](https://github.com/huggingface/accelerate) | [LeRobot Visualizer](https://github.com/huggingface/lerobot-dataset-visualizer)

<details open>
<summary><b>GTSAM</b> — 6 merged</summary>

| PR | Description |
|---|---|
| [#2456](https://github.com/borglab/gtsam/pull/2456) | Fix `enforceConsistency_` in BatchFixedLagSmoother -- first-estimates Jacobian logic was silently broken |
| [#2463](https://github.com/borglab/gtsam/pull/2463) | Fix incorrect key in cheirality error message for PPP/PPPC factors |
| [#2464](https://github.com/borglab/gtsam/pull/2464) | Fix `tMin_` reset when an iteration has zero duration |
| [#2465](https://github.com/borglab/gtsam/pull/2465) | Reject negative sigma values in noise model constructors |
| [#2467](https://github.com/borglab/gtsam/pull/2467) | Fix `LinearContainerFactor::rekey()` segfault without linearization point |
| [#2471](https://github.com/borglab/gtsam/pull/2471) | Rename Python reserved keywords in wrapper interface files |

</details>

<details open>
<summary><b>HuggingFace LeRobot</b> — 4 merged</summary>

| PR | Description |
|---|---|
| [#2486](https://github.com/huggingface/lerobot/pull/2486) | Enable `torch.compile` for DiffusionPolicy -- inference speedup for real-time robot control |
| [#3016](https://github.com/huggingface/lerobot/pull/3016) | Replace assertions with proper exceptions in video frame decoding |
| [#3017](https://github.com/huggingface/lerobot/pull/3017) | Fix missing config file in pip installs causing AttributeError crash |
| [#3063](https://github.com/huggingface/lerobot/pull/3063) | Ensure queue and process cleanup on abnormal exit |

</details>

<details>
<summary><b>PyTorch RL</b> — 3 merged</summary>

| PR | Description |
|---|---|
| [#3530](https://github.com/pytorch/rl/pull/3530) | Fix missing raise, incorrect `__torch_function__` return, and off-by-one in RayCollector |
| [#3589](https://github.com/pytorch/rl/pull/3589) | Fix `MultiOneHot.to_numpy()` returning scalar instead of per-space array |
| [#3590](https://github.com/pytorch/rl/pull/3590) | Add `set_at_`, `set_`, `update_` in-place write methods to ReplayBuffer |

</details>

<details>
<summary><b>Rerun</b> — 3 merged</summary>

| PR | Description |
|---|---|
| [#12672](https://github.com/rerun-io/rerun/pull/12672) | Fix incorrect byte unit conversion values in render benchmark |
| [#12673](https://github.com/rerun-io/rerun/pull/12673) | Reuse precomputed timelines dict in `send_columns` instead of re-iterating |
| [#12674](https://github.com/rerun-io/rerun/pull/12674) | Fix wrong variable in error message for extra args in `log()` |

</details>

<details>
<summary><b>RSL_RL</b> — 2 merged</summary>

| PR | Description |
|---|---|
| [#180](https://github.com/leggedrobotics/rsl_rl/pull/180) | Fix missing raise, wrong RND broadcast index, and variable typo |
| [#181](https://github.com/leggedrobotics/rsl_rl/pull/181) | Fix mutable default arguments and replace assertions with proper exceptions |

</details>

<details>
<summary><b>HuggingFace Transformers</b> — 1 merged</summary>

| PR | Description |
|---|---|
| [#44287](https://github.com/huggingface/transformers/pull/44287) | Fix mutable default arguments and resource leaks |

</details>

<details>
<summary><b>HuggingFace Accelerate</b> — 1 merged</summary>

| PR | Description |
|---|---|
| [#3944](https://github.com/huggingface/accelerate/pull/3944) | Fix mutable default in Megatron init and IndexError on empty ModuleList |

</details>

<details>
<summary><b>LeRobot Dataset Visualizer</b> — 1 merged</summary>

| PR | Description |
|---|---|
| [#57](https://github.com/huggingface/lerobot-dataset-visualizer/pull/57) | Add Doctor tab integrating [lerobot-doctor](https://github.com/jashshah999/lerobot-doctor) diagnostics into the visualizer |

</details>
