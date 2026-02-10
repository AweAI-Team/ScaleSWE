# Immersion in the GitHub Universe: Scaling Coding Agents to Mastery

<div align="center">

[![arXiv](https://img.shields.io/badge/arXiv-2301.00000-b31b1b.svg)](https://arxiv.org/abs/2301.00000)
[![Hugging Face Datasets](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Datasets-blue)](https://huggingface.co/datasets/Awe-AI/Scale-SWE)
[![Hugging Face Models](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Models-yellow)](https://huggingface.co/Awe-AI/Scale-SWE)
[![License](https://img.shields.io/badge/License-CC%20BY%204.0-green.svg)](LICENSE)
<br>

**🚧 Release Notice:** The datasets and models are currently under internal review. <br>
We expect to open-source them within **one month**.
</div>

<!-- > [!IMPORTANT]
> **Release Notice:** Our datasets and models are currently undergoing **internal review**. We are committed to open-sourcing them as soon as possible, with an expected release within **one month**. Stay tuned! -->


![](figures/scale_swe.drawio.png)

## 🔥 Highlights

- Massive Scale: Processed 6M+ Pull Requests from 5,200+ repositories. 100k verified instances (Scale-SWE-Data), offering unmatched diversity and complexity.
- Strong Performance: Scale-SWE-Agent(30A3B) achieves 64% on SWE-Bench-Verified.

## 🤖 Results
We fine-tuned Qwen-30B-A3B-Instruct on our synthesized trajectories.
| Models | Base Model | SWE-bench (V) |
| :--- | :--- | :---: |
| **Proprietary Models** | | |
| GPT-5.2 Thinking OpenAI (2025) | - | **80.0** |
| Claude Sonnet 4.5 Anthropic (2025b) | - | 77.2 |
| Gemini 3 Pro Google (2025) | - | 76.2 |
| MiniMax-M2.1 MiniMax AI (2025) | - | 74.0 |
| GLM-4.7 Zhipu AI (2025) | - | 73.8 |
| DeepSeek-V3.2 Liu et al. (2025) | - | 73.1 |
| Kimi K2 Thinking Team et al. (2025) | - | 71.3 |
| **Open Source Methods** | | |
| SWE-Gym-32B Pan et al. (2024) | Qwen-2.5 coder | 20.6 |
| SWE-Fixer-72B Xie et al. (2025) | Qwen2.5-72B | 32.8 |
| R2E-Gym-32B Jain et al. (2025) | Qwen-2.5-Coder | 34.4 |
| SWE-rebench-72B Golubev et al. (2025) | Qwen2.5-72B-Instruct | 39.0 |
| SWE-smith-32B Yang et al. (2025a) | Qwen2.5-32B | 40.2 |
| SWE-RL Wei et al. (2025) | Llama3-70B | 41.0 |
| Skywork-SWE-32B Zeng et al. (2025) | Qwen2.5-Coder-32B-Instruct | 47.9 |
| SWE-Mirror-LM-32B Wang et al. (2025a) | Qwen2.5-Coder-32B-Instruct | 52.2 |
| SWE-Lego-32B Tao et al. (2026) | Qwen3-32B | 52.6 |
| KAT-Dev-32B Zhan et al. (2025) | - | **62.4** |
| **Models of the same size** | | |
| Qwen3-30B-A3B-Instruct Team (2025) | - | 22.0 |
| Qwen3-Coder-30B-A3B-Instruct Team (2025) | - | 51.6 |
| GLM-4.7-Flash-30A3B Zhipu AI (2026) | - | **59.2** |
| **Our Model** | | |
| **Scale-SWE-Agent** | **Qwen3-30B-A3B-Instruct** | **64.0** |

## 📖 Citation

If you find this project useful for your research, please consider citing our paper:
```

```

## 📄 License

This project is licensed under the CC BY 4.0 License - see the [LICENSE](LICENSE) file for details.