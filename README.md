## Hi, I'm Alexander 👋

Software developer at [54Grad Software](https://github.com/code-with-dot-us) in northern Germany.
**PHP and Node/TypeScript** pay the bills; **Python and Go** are where I spend my evenings.

Most of my open source work orbits [InvokeAI](https://github.com/invoke-ai/InvokeAI) — I contribute
upstream and build the tooling around it that I kept wishing existed.

---

### 🎨 InvokeAI ecosystem

**Tools**

| Project | What it does | Stack |
|---|---|---|
| [invoke-openai-proxy](https://github.com/Pfannkuchensack/openaiapi2invokeai-go) | OpenAI-compatible image API in front of InvokeAI, so Open-WebUI & co. can generate against a local install. Single static binary, embedded admin UI. | Go |
| [InvokeAI DB Tool](https://github.com/Pfannkuchensack/sqlite_invokeai_db_tool) | Syncs, restores and cleans the InvokeAI SQLite database against your outputs folder, recovering metadata straight from PNGs. | Electron |
| [invokeai-bench](https://github.com/Pfannkuchensack/invoke_bench_tool) | Benchmarks txt2img/img2img across SD 1.5 → SDXL, FLUX.1/2, SD3, Z-Image and CogView4, with JSON export and run comparison. | Python |
| [invokeai-docker-build](https://github.com/Pfannkuchensack/invokeai-docker-build) | CUDA/CPU/ROCm images of my InvokeAI fork, published to GHCR. | Docker |

**Nodes**

| Project | What it does |
|---|---|
| [Qwen3 Prompt Pro](https://github.com/Pfannkuchensack/invokenode_qwen3_prompt_pro) | Reuses the already-loaded Qwen3 encoder as an LLM to expand prompts, then conditions Z-Image and Flux Klein in one node. |
| [Krea-2 Prompt Weighting](https://github.com/Pfannkuchensack/krea2_prompt_weighting) | Per-token weighting for Krea-2 — `(blonde:0)`, `(a red apple:-1)` — in ComfyUI, A1111 and compel notation. |
| [Winzige Banane 🍌](https://github.com/Pfannkuchensack/winzige_banane_invokeai_node) | Gemini 2.5 Flash / 3 Pro image generation. German for "tiny banana", after Google's *Nano Banana* codename. |
| [Z-Image Seed Variance](https://github.com/Pfannkuchensack/invokeai-z-image-seed-variance-enhancer) | Restores seed-to-seed variety in Z-Image-Turbo. |
| [FLUX.2 Hildegard Refiner](https://github.com/Pfannkuchensack/flux2_hildegard_refiner) | Tile-based refinement for FLUX.2 Klein: three explicit reference slots (tile, position, global) at full resolution instead of the stock clamped reference path. Ported from 42lux's ComfyUI scheme. |
| [Workflow Package](https://github.com/Pfannkuchensack/Pfannkuchensack-Workflow-Package) | A library of composable workflows that install themselves into InvokeAI. |

### 🕹️ Other things I've built

Game jam entries ([GMTK 2021](https://github.com/Pfannkuchensack/GMTK2021-game),
[Global Game Jam 2022](https://github.com/Pfannkuchensack/GGJ2022-game),
[Lost Shapes](https://github.com/Pfannkuchensack/Lost-Shapes)), a
[quiz built on InvokeAI's workflow engine](https://github.com/Pfannkuchensack/invoke_workflow_quiz),
and hardware bits and pieces from [Chaostreff Flensburg/Chaos Computer Club Flensburg](https://github.com/chaostreff-flensburg).

### 🎩

On GitHub since 2012 · Arctic Code Vault contributor
