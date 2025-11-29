# mT5-SFT-and-DPO-Training
This repository contains two Jupyter notebooks demonstrating how to fine-tune and align the mT5 model using modern LLM training techniques:

- **Supervised Fine-Tuning (SFT)** – trains the model on high-quality instruction–response pairs.
- **Direct Preference Optimization (DPO)** – aligns the model to human preferences using chosen vs rejected answers.

These two stages form a simplified version of how modern LLMs such as ChatGPT or LLaMA-based models are aligned.

---

## Overview

The goal of this project is to explore the alignment capabilities of **mT5**, a multilingual sequence-to-sequence model, through:

### Supervised Fine-Tuning (SFT)
Helps the model learn the desired instruction-following behavior.

### Direct Preference Optimization (DPO)
Makes the model prefer better answers using pairwise comparison, improving:
- Helpfulness  
- Safety  
- Coherence  
- Instruction-following reliability  


