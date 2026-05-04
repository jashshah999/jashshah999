Hi, I'm Jash.

[![Email](https://img.shields.io/badge/Email-jashshah.999%40gmail.com-red?style=flat-square&logo=gmail&logoColor=white)](mailto:jashshah.999@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Jash%20Shah-blue?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jash-shah-999-new/)

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=jashshah999&show_icons=true&theme=dark&count_private=true&show=prs_merged&include_all_commits=true)

---

## Open Source Contributions

24 PRs merged across 10 repos. 37 open PRs across 14 repos.

[GTSAM](https://github.com/borglab/gtsam) | [LeRobot](https://github.com/huggingface/lerobot) | [PyTorch](https://github.com/pytorch/pytorch) | [PyTorch RL](https://github.com/pytorch/rl) | [Torchvision](https://github.com/pytorch/vision) | [Rerun](https://github.com/rerun-io/rerun) | [RSL_RL](https://github.com/leggedrobotics/rsl_rl) | [Transformers](https://github.com/huggingface/transformers) | [Accelerate](https://github.com/huggingface/accelerate) | [SciPy](https://github.com/scipy/scipy) | [JAX](https://github.com/jax-ml/jax) | [gsplat](https://github.com/nerfstudio-project/gsplat) | [TorchMetrics](https://github.com/Lightning-AI/torchmetrics) | [Diffusers](https://github.com/huggingface/diffusers)

## Projects

| Project | Description |
|---|---|
| [vggt-factor-refinement](https://github.com/jashshah999/vggt-factor-refinement) | Factor graph refinement of VGGT for long video camera pose estimation. 70% ATE improvement over naive stitching on TUM-RGBD and Replica. |
| [gtsam-splatfactors](https://github.com/jashshah999/gtsam-splatfactors) | Gaussian Splatting meets Factor Graph SLAM. iSAM2 pose optimization with differentiable rendering factors. |
| [lerobot-doctor](https://github.com/jashshah999/lerobot-doctor) | Diagnostic tool for LeRobot datasets. Integrated into the official HF dataset visualizer. |

---

<details open>
<summary><b>GTSAM</b> — 6 merged, 3 open</summary>

| PR | Description |
|---|---|
| [#2456](https://github.com/borglab/gtsam/pull/2456) | Fix `enforceConsistency_` in BatchFixedLagSmoother |
| [#2463](https://github.com/borglab/gtsam/pull/2463) | Fix incorrect key in cheirality error message for PPP/PPPC factors |
| [#2464](https://github.com/borglab/gtsam/pull/2464) | Fix `tMin_` reset when an iteration has zero duration |
| [#2465](https://github.com/borglab/gtsam/pull/2465) | Reject negative sigma values in noise model constructors |
| [#2467](https://github.com/borglab/gtsam/pull/2467) | Fix `LinearContainerFactor::rekey()` segfault without linearization point |
| [#2471](https://github.com/borglab/gtsam/pull/2471) | Rename Python reserved keywords in wrapper interface files |

</details>

<details open>
<summary><b>HuggingFace LeRobot</b> — 4 merged, 17 open</summary>

| PR | Description |
|---|---|
| [#2486](https://github.com/huggingface/lerobot/pull/2486) | Enable `torch.compile` for DiffusionPolicy inference |
| [#3016](https://github.com/huggingface/lerobot/pull/3016) | Replace assertions with proper exceptions in video frame decoding |
| [#3017](https://github.com/huggingface/lerobot/pull/3017) | Fix missing config file in pip installs causing AttributeError crash |
| [#3063](https://github.com/huggingface/lerobot/pull/3063) | Ensure queue and process cleanup on abnormal exit |
| [#3485](https://github.com/huggingface/lerobot/pull/3485) | Fix PEFT LoRA resume from Hub (PosixPath + double wrap) |
| [#3501](https://github.com/huggingface/lerobot/pull/3501) | Fix streaming dataset + EpisodeAwareSampler crash |
| [#3502](https://github.com/huggingface/lerobot/pull/3502) | Add validation loss with episode-level train/val split |
| [#3503](https://github.com/huggingface/lerobot/pull/3503) | Add gradient checkpointing for DiffusionPolicy |

</details>

<details>
<summary><b>PyTorch</b> — 4 open</summary>

| PR | Description |
|---|---|
| [#178664](https://github.com/pytorch/pytorch/pull/178664) | Fix igamma backward for negative derivative |
| [#178228](https://github.com/pytorch/pytorch/pull/178228) | Fix addr backward |
| [#178209](https://github.com/pytorch/pytorch/pull/178209) | Fix batch_norm eval mode |
| [#175958](https://github.com/pytorch/pytorch/pull/175958) | Fix checkpoint off-by-one |

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
<summary><b>SciPy</b> — 2 open</summary>

| PR | Description |
|---|---|
| [#25081](https://github.com/scipy/scipy/pull/25081) | Fix `invgauss.logsf` NaN for small mu (numerical stability) |
| [#25095](https://github.com/scipy/scipy/pull/25095) | Fix RecursionError in `cspline1d_eval` for N=1 |

</details>

<details>
<summary><b>gsplat</b> — 2 open</summary>

| PR | Description |
|---|---|
| [#938](https://github.com/nerfstudio-project/gsplat/pull/938) | Fix backgrounds shape assertion when packed=True |
| [#939](https://github.com/nerfstudio-project/gsplat/pull/939) | Add MCMC cap_max pruning for SfM initialization |

</details>

<details>
<summary><b>Torchvision</b> — 1 open</summary>

| PR | Description |
|---|---|
| [#9485](https://github.com/pytorch/vision/pull/9485) | Fix `convert_image_dtype` overflow for float16/bfloat16 |

</details>

<details>
<summary><b>JAX</b> — 1 open</summary>

| PR | Description |
|---|---|
| [#37358](https://github.com/jax-ml/jax/pull/37358) | Use two-pass variance in `nn.standardize` for numerical stability |

</details>

<details>
<summary><b>TorchMetrics</b> — 1 open</summary>

| PR | Description |
|---|---|
| [#3371](https://github.com/Lightning-AI/torchmetrics/pull/3371) | Fix MCC returning wrong values when denominator is zero |

</details>

<details>
<summary><b>HuggingFace Transformers</b> — 1 merged, 1 open</summary>

| PR | Description |
|---|---|
| [#44287](https://github.com/huggingface/transformers/pull/44287) | Fix mutable default arguments and resource leaks |
| [#45771](https://github.com/huggingface/transformers/pull/45771) | Replace Conv3d with F.linear in Qwen3VL patch embed (~50,000x speedup) |

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
