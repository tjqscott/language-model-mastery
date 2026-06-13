# Language Model Mastery

[@TheAhmadOsman](https://x.com/TheAhmadOsman) published a list of 26 essential papers for understanding modern LLMs. This repo works through all of them. Each paper gets a notes file. Each cluster gets a synthesis. The clusters trace distinct threads in how the field developed, and the opinions in those syntheses are earned after reading, not before.

[Taylor Scott](https://tjqscott.com)

---

### 01 · [Transformers](./1-transformers/index.md)
*Start with Alammar. Then Vaswani. The architecture, positional encoding, and memory efficiency decisions from 2017–2022 that nobody has meaningfully displaced.*

| Paper | Authors | Year | Status |
|---|---|---|---|
| [The Illustrated Transformer](./1-transformers/alammar.md) | Jay Alammar | 2018 | ⬜ |
| [Attention Is All You Need](./1-transformers/vaswani.md) | Vaswani et al. | 2017 | ⬜ |
| [BERT](./1-transformers/devlin.md) | Devlin et al. | 2018 | ⬜ |
| [RoFormer / RoPE](./1-transformers/su.md) | Su et al. | 2021 | ⬜ |
| [FlashAttention](./1-transformers/dao.md) | Dao et al. | 2022 | ⬜ |

---

### 02a · [Data Scaling](./2a-data-scaling/index.md)
*Kaplan said scale the parameters. Chinchilla said scale the tokens. LLaMA proved you could do both on a budget. A single argument that ran from 2020 to 2023 and rewrote how everyone trains models.*

| Paper | Authors | Year | Status |
|---|---|---|---|
| [Scaling Laws for Neural LMs](./2a-data-scaling/kaplan.md) | Kaplan et al. | 2020 | ⬜ |
| [Chinchilla](./2a-data-scaling/hoffmann.md) | Hoffmann et al. | 2022 | ⬜ |
| [PaLM](./2a-data-scaling/chowdhery.md) | Chowdhery et al. | 2022 | ⬜ |
| [LLaMA](./2a-data-scaling/touvron.md) | Touvron et al. | 2023 | ⬜ |
| [Textbooks Are All You Need](./2a-data-scaling/gunasekar.md) | Gunasekar et al. | 2023 | ⬜ |

---

### 02b · [Sparsity Scaling](./2b-sparsity-scaling/index.md)
*A different lever entirely. MoE decouples parameter count from inference cost — bigger model, same compute. Shazeer planted the idea in 2017. By 2024 it was the architecture behind most frontier models.*

| Paper | Authors | Year | Status |
|---|---|---|---|
| [Sparsely-Gated MoE](./2b-sparsity-scaling/shazeer.md) | Shazeer et al. | 2017 | ⬜ |
| [Switch Transformers](./2b-sparsity-scaling/fedus.md) | Fedus et al. | 2021 | ⬜ |
| [GLaM](./2b-sparsity-scaling/du.md) | Du et al. | 2022 | ⬜ |
| [Sparse Upcycling](./2b-sparsity-scaling/komatsuzaki.md) | Komatsuzaki et al. | 2022 | ⬜ |
| [Mixtral of Experts](./2b-sparsity-scaling/mistral.md) | Mistral AI | 2024 | ⬜ |
| [Qwen3 Technical Report](./2b-sparsity-scaling/yang.md) | Yang et al. | 2025 | ⬜ |

---

### 03 · [Post-Training](./3-post-training/index.md)
*Pretraining gives you a model that predicts text. These three papers cover what it took to turn that into something that follows instructions, reflects preferences, and reasons under its own initiative.*

| Paper | Authors | Year | Status |
|---|---|---|---|
| [InstructGPT](./3-post-training/ouyang.md) | Ouyang et al. | 2022 | ⬜ |
| [DPO](./3-post-training/rafailov.md) | Rafailov et al. | 2023 | ⬜ |
| [DeepSeek-R1](./3-post-training/guo.md) | Guo et al. | 2025 | ⬜ |

---

### 04 · [Inference](./4-inference/index.md)
*What you can get out of a model without touching the weights. GPT-3 established prompting as a capability unlock. CoT showed reasoning could be elicited, not just trained. ReAct handed models tools. RAG gave them memory.*

| Paper | Authors | Year | Status |
|---|---|---|---|
| [GPT-3 / Few-Shot Learners](./4-inference/brown.md) | Brown et al. | 2020 | ⬜ |
| [Chain-of-Thought Prompting](./4-inference/wei.md) | Wei et al. | 2022 | ⬜ |
| [ReAct](./4-inference/yao.md) | Yao et al. | 2022 | ⬜ |
| [RAG](./4-inference/lewis.md) | Lewis et al. | 2020 | ⬜ |

---

### 05 · [Internals](./5-internals/index.md)
*Monosemanticity decomposes a model into millions of readable features. The Platonic Representation Hypothesis asks whether all large models are converging on the same internal picture of the world. The Smol Training Playbook closes the loop — now go build one.*

| Paper | Authors | Year | Status |
|---|---|---|---|
| [Scaling Monosemanticity](./5-internals/templeton.md) | Templeton et al. | 2024 | ⬜ |
| [The Platonic Representation Hypothesis](./5-internals/huh.md) | Huh et al. | 2024 | ⬜ |
| [The Smol Training Playbook](./5-internals/huggingface.md) | Hugging Face | 2025 | ⬜ |

---

*Built on [@TheAhmadOsman](https://x.com/TheAhmadOsman)'s original list. Maintained by [Taylor Scott](https://tjqscott.com).*
