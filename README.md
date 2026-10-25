# Saloni Garg

Staff Machine Learning Engineer at Adobe (Firefly), San Jose, CA. I work on GPU-accelerated AI systems, post-training, and large-scale generative models.

[Website](https://saloni-garg.github.io/) · [LinkedIn](https://www.linkedin.com/in/saloni-garg)

## Open source contributions

Recent work on a numerical bug class in GRPO advantage computation: reward groups in which every response scores the same can pick up a nonzero advantage from float32 group statistics. Fixes with regression tests, open in:

[![OpenEnv PR%20%231477](https://img.shields.io/badge/OpenEnv-PR%20%231477-2ea44f?style=flat-square&logo=github)](https://github.com/openenv/OpenEnv/pull/1477) [![verl PR%20%238349](https://img.shields.io/badge/verl-PR%20%238349-2ea44f?style=flat-square&logo=github)](https://github.com/verl-project/verl/pull/8349) [![slime PR%20%232494](https://img.shields.io/badge/slime-PR%20%232494-2ea44f?style=flat-square&logo=github)](https://github.com/THUDM/slime/pull/2494) [![SkyRL PR%20%232531](https://img.shields.io/badge/SkyRL-PR%20%232531-2ea44f?style=flat-square&logo=github)](https://github.com/NovaSky-AI/SkyRL/pull/2531) [![OpenRLHF PR%20%231383](https://img.shields.io/badge/OpenRLHF-PR%20%231383-2ea44f?style=flat-square&logo=github)](https://github.com/OpenRLHF/OpenRLHF/pull/1383) [![EasyR1 PR%20%2311020](https://img.shields.io/badge/EasyR1-PR%20%2311020-2ea44f?style=flat-square&logo=github)](https://github.com/hiyouga/EasyR1/pull/11020)

And in Triton's interpreter, a fix for NaN/Inf conversions: FP8 special codes decode as Inf/NaN instead of finite numbers, and RTZ downcasts no longer turn small-payload NaNs into infinities:

[![Triton PR #12489](https://img.shields.io/badge/Triton-PR%20%2312489-2ea44f?style=flat-square&logo=github)](https://github.com/triton-lang/triton/pull/12489)

And in TorchTPU's dynamic view decomposition, two fixes: a strided view can no longer be given a base larger than its storage, and 0-d views with a storage offset no longer crash with an IndexError:

[![TorchTPU PR #5846](https://img.shields.io/badge/TorchTPU-PR%20%235846-2ea44f?style=flat-square&logo=github)](https://github.com/google-pytorch/torch_tpu/pull/5846) [![TorchTPU PR #5847](https://img.shields.io/badge/TorchTPU-PR%20%235847-2ea44f?style=flat-square&logo=github)](https://github.com/google-pytorch/torch_tpu/pull/5847)

## Selected projects

- gpu-train-debug: an RL environment for GPU training failure diagnosis, published on the Prime Intellect Hub in the Verifiers format. Dataset on [Hugging Face](https://huggingface.co/datasets/sluuu/gpu-train-debug).
- [jev-max](https://github.com/saloni-garg/jev-max): a browser agent that handles the real web (shadow DOM, iframes, canvas fallback, multi-tab).
- [memfix](https://github.com/saloni-garg/memfix): a provenance-first, correctable memory layer for AI agents, with an MCP server.
