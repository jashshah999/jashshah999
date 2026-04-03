Hi, I'm Jash.

[![Email](https://img.shields.io/badge/Email-jashshah.999%40gmail.com-red?style=flat-square&logo=gmail&logoColor=white)](mailto:jashshah.999@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Jash%20Shah-blue?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jash-shah-999-new/)

---

## Open Source Contributions

17 PRs merged across 7 repos. 27+ PRs open across 9 repos.

[GTSAM](https://github.com/borglab/gtsam) | [LeRobot](https://github.com/huggingface/lerobot) | [Rerun](https://github.com/rerun-io/rerun) | [PyTorch RL](https://github.com/pytorch/rl) | [Transformers](https://github.com/huggingface/transformers) | [Accelerate](https://github.com/huggingface/accelerate) | [RSL_RL](https://github.com/leggedrobotics/rsl_rl) | [Diffusers](https://github.com/huggingface/diffusers) | [PyTorch](https://github.com/pytorch/pytorch) | [Gymnasium](https://github.com/Farama-Foundation/Gymnasium) | [MuJoCo](https://github.com/google-deepmind/mujoco)

<details open>
<summary><b>GTSAM</b> — 5 merged, 2 open</summary>

| PR | Description |
|---|---|
| [#2456](https://github.com/borglab/gtsam/pull/2456) | Fix `enforceConsistency_` in BatchFixedLagSmoother -- first-estimates Jacobian logic was silently broken |
| [#2463](https://github.com/borglab/gtsam/pull/2463) | Fix incorrect key in cheirality error message for PPP/PPPC factors |
| [#2464](https://github.com/borglab/gtsam/pull/2464) | Fix `tMin_` reset when an iteration has zero duration |
| [#2465](https://github.com/borglab/gtsam/pull/2465) | Reject negative sigma values in noise model constructors |
| [#2467](https://github.com/borglab/gtsam/pull/2467) | Fix `LinearContainerFactor::rekey()` segfault without linearization point |
| [#2466](https://github.com/borglab/gtsam/pull/2466) | *(open)* |
| [#2471](https://github.com/borglab/gtsam/pull/2471) | *(open)* |

</details>

<details>
<summary><b>HuggingFace LeRobot</b> — 3 merged, 14 open</summary>

| PR | Description |
|---|---|
| [#2486](https://github.com/huggingface/lerobot/pull/2486) | Enable `torch.compile` for DiffusionPolicy -- inference speedup for real-time robot control |
| [#3016](https://github.com/huggingface/lerobot/pull/3016) | Replace assertions with proper exceptions in video frame decoding |
| [#3017](https://github.com/huggingface/lerobot/pull/3017) | Fix missing config file in pip installs causing AttributeError crash |
| [#3145](https://github.com/huggingface/lerobot/pull/3145) | *(open)* Support YAML `policy.path` config |
| [#3158](https://github.com/huggingface/lerobot/pull/3158) | *(open)* Async image resize in dataloader |
| [#3159](https://github.com/huggingface/lerobot/pull/3159) | *(open)* Use `select()` for multi-index HF dataset queries |
| [#3160](https://github.com/huggingface/lerobot/pull/3160) | *(open)* Skip unnecessary dataset reloads |
| [#3209](https://github.com/huggingface/lerobot/pull/3209) | *(open)* Pi0 cudagraph support |
| [#3123](https://github.com/huggingface/lerobot/pull/3123) | *(open)* |
| [#3061](https://github.com/huggingface/lerobot/pull/3061) | *(open)* |
| [#3062](https://github.com/huggingface/lerobot/pull/3062) | *(open)* |
| [#3063](https://github.com/huggingface/lerobot/pull/3063) | *(open)* |
| [#3038](https://github.com/huggingface/lerobot/pull/3038) | *(open)* |
| [#3037](https://github.com/huggingface/lerobot/pull/3037) | *(open)* |
| [#3025](https://github.com/huggingface/lerobot/pull/3025) | *(open)* |
| [#3015](https://github.com/huggingface/lerobot/pull/3015) | *(open)* |
| [#3014](https://github.com/huggingface/lerobot/pull/3014) | *(open)* |

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
<summary><b>PyTorch RL</b> — 1 merged, 2 open</summary>

| PR | Description |
|---|---|
| [#3530](https://github.com/pytorch/rl/pull/3530) | Fix missing raise, incorrect `__torch_function__` return, and off-by-one in RayCollector |
| [#3589](https://github.com/pytorch/rl/pull/3589) | *(open)* Fix `MultiOneHot.to_numpy()` returning scalar instead of per-space array |
| [#3590](https://github.com/pytorch/rl/pull/3590) | *(open)* Add `set_at_`, `set_`, `update_` in-place write methods to ReplayBuffer |

</details>

<details>
<summary><b>PyTorch</b> — 5 open</summary>

| PR | Description |
|---|---|
| [#175957](https://github.com/pytorch/pytorch/pull/175957) | *(open)* |
| [#175958](https://github.com/pytorch/pytorch/pull/175958) | *(open)* |
| [#178228](https://github.com/pytorch/pytorch/pull/178228) | *(open)* `addr` backward fix |
| [#178209](https://github.com/pytorch/pytorch/pull/178209) | *(open)* `batch_norm` eval fix |
| [#178664](https://github.com/pytorch/pytorch/pull/178664) | *(open)* `igamma` backward fix |

</details>

<details>
<summary><b>HuggingFace Transformers</b> — 1 merged, 1 open</summary>

| PR | Description |
|---|---|
| [#44287](https://github.com/huggingface/transformers/pull/44287) | Fix mutable default arguments and resource leaks |
| [#45222](https://github.com/huggingface/transformers/pull/45222) | *(open)* Fix Gemma 3/4 text-only training crash -- default `token_type_ids` to zeros |

</details>

<details>
<summary><b>HuggingFace Accelerate</b> — 1 PR</summary>

| PR | Description |
|---|---|
| [#3944](https://github.com/huggingface/accelerate/pull/3944) | Fix mutable default in Megatron init and IndexError on empty ModuleList |

</details>

<details>
<summary><b>HuggingFace Diffusers</b> — 2 open</summary>

| PR | Description |
|---|---|
| [#13190](https://github.com/huggingface/diffusers/pull/13190) | *(open)* |
| [#13185](https://github.com/huggingface/diffusers/pull/13185) | *(open)* |

</details>

<details>
<summary><b>RSL_RL</b> — 2 PRs</summary>

| PR | Description |
|---|---|
| [#180](https://github.com/leggedrobotics/rsl_rl/pull/180) | Fix missing raise, wrong RND broadcast index, and variable typo |
| [#181](https://github.com/leggedrobotics/rsl_rl/pull/181) | Fix mutable default arguments and replace assertions with proper exceptions |

</details>

<details>
<summary><b>Gymnasium</b> — 1 open</summary>

| PR | Description |
|---|---|
| [#1533](https://github.com/Farama-Foundation/Gymnasium/pull/1533) | *(open)* |

</details>

<details>
<summary><b>MuJoCo</b> — 1 open</summary>

| PR | Description |
|---|---|
| [#3135](https://github.com/google-deepmind/mujoco/pull/3135) | *(open)* |

</details>
