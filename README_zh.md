# Awesome Prompt Inversion [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

🌍 *语言: [English](README.md) | [中文](README_zh.md)*

<p align="center">
  <img src="img/prompt_cn.png" alt="Prompt Inversion 概览" width="800">
  <br>
  <em>图像由 <strong>Gemini</strong> 生成</em>
</p>




这是一个精心整理的精选资源列表，专门聚焦于基础模型（大语言模型、视觉语言模型和扩散模型）中的 **Prompt Inversion（提示词反演/逆向）** 相关的研究论文、工具、数据集和资源。

**Prompt Inversion**（也称为提示词提取、逆向提示或图像到提示词）是指对模型进行逆向工程，以发现生成特定输出（例如目标图像、特定文本响应或隐藏的模型状态）的精确或最佳离散文本提示词的过程。

本仓库主要关注以下方向：

* **Image-to-Prompt (图像到提示词 - 扩散模型/VLMs):** 从生成的图像或真实图像中提取文本提示词。
* **Output-to-Prompt (输出到提示词 - LLMs):** 基于生成的文本重构用户的输入或系统提示词。
* **安全与提示词窃取 (Security & Prompt Stealing):** 在黑盒模型中提取隐藏的系统提示词、评估模型脆弱性或暴露记忆数据的对抗性技术。

---

## 📋 目录

- [📝 论文 (Papers)](#-论文-papers)
  - [图像到提示词与扩散模型逆向 (Image-to-Prompt &amp; Diffusion Inversion)](#图像到提示词与扩散模型逆向-image-to-prompt--diffusion-inversion)
  - [大模型提示词提取与逆向提示 (LLM Prompt Extraction &amp; Reverse Prompting)](#大模型提示词提取与逆向提示-llm-prompt-extraction--reverse-prompting)
  - [安全：提示词窃取攻击 (Security: Prompt Stealing Attacks)](#安全提示词窃取攻击-security-prompt-stealing-attacks)
- [🛠️ 工具与框架 (Tools &amp; Frameworks)](#️-工具与框架-tools--frameworks)
- [🤝 参与贡献 (Contributing)](#-参与贡献-contributing)
- [📜 开源协议 (License)](#-开源协议-license)

---

## 📝 论文 (Papers)

### 扩散模型中的提示词逆向 (Diffusion Inversion)

- **Towards Effective Prompt Stealing Attack against Text-to-Image Diffusion Models** - *Zhao et al., NDSS 2026.* [[Paper](https://arxiv.org/abs/2508.06837)] [[Code](https://github.com/Shiqian-Zhao996/Prometheus)]
- **Reinforcement Learning-Based Prompt Template Stealing for Text-to-Image Models** -  *Xiaotian Zou., AAAI, 2026* . [[Paper](https://arxiv.org/abs/2510.00046)] [[None-Code]()]
- **Hard Prompts Made Easy: Gradient-Based Discrete Optimization for Prompt Tuning and Discovery** - *Wen et al., NeurIPS 2023.*  [[Paper](https://arxiv.org/abs/2302.03668)] [[Code](https://github.com/YuxinWenRick/hard-prompts-made-easy)]

### 语言模型提示词提取与逆向提示 (LLM )

* **Prompt Stealing Attacks Against Large Language Models** - *Sha et al., 2024.* [[Paper](https://arxiv.org/abs/2402.12959)] [[Code](https://www.google.com/search?q=%E6%97%A0%E5%85%AC%E5%BC%80%E6%BA%90%E7%A0%81)]

### 其他与提示词相关的Paper

图像描述、提示词优化、提示词生成等

**PromptCap: Prompt-Guided Task-Aware Image Captioning** - *Hu et al., ICCV 2023.* 。 [[Paper](https://arxiv.org/abs/2211.09699)] [[Code](https://github.com/Yushi-Hu/PromptCap)]

**AUTOPROMPT: Eliciting Knowledge from Language Models with Automatically Generated Prompts** - *Shin et al., 2020.* [[Paper](https://arxiv.org/abs/2010.15980)] [[Code](http://ucinlp.github.io/autoprompt)]

---

## 🛠️ 工具与框架 (Tools & Frameworks)

- [CLIP Interrogator](https://github.com/pharmapsychotic/clip-interrogator) - 结合 CLIP 和 BLIP 从图像中逆向工程提示词的工具。
- [Diffusion ModeL](https://huggingface.co/docs/diffusers/index) - 扩散模型。

---

## 🤝 参与贡献 (Contributing)

非常欢迎您的贡献！如果您知道任何专门针对 **Prompt Inversion** 或 **Prompt Extraction** 的优秀论文、工具或资源，请随时提交 Pull Request。

请确保您的 PR 遵循以下指南：

- 推荐的论文/工具必须严格与从输出/图像中提取、重构或优化**离散文本提示词**相关。
- 请使用提供的论文格式：`**Title** - *Authors, Venue Year.* [[Paper](link)] [[Code](link)]`

---

## 📜 开源协议 (License)

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)
