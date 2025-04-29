---
layout: page
title: "Projects"
permalink: /projects/
---

Below is a list of some projects I’ve worked on:

---

### 🤖 Self-Improving Debate Framework for SLMs

**PolyMind** implements a mixture-of-agents architecture where multiple expert models are fine-tuned on specific domains and correct each other through shared memory. The memory is created with the expert's responses and the critic's feedback.

**Key Features:**

- Multiple expert agents that can be fine-tuned on specific domains  
- A critic agent that evaluates expert responses  
- A debate mechanism for self-improvement  
- Memory-augmented learning using simple dictionaries  
- Statistical analysis of agent performance  

**Tech:** Hugging Face Transformers, LoRA, T5, Gemma  
**Datasets:** SAMSum, OPUS (German-English)  

📄 [Read report (PDF)](/assets/reports/PolyMind.pdf)  
💻 [View on GitHub](https://github.com/rathorevedant99/nlp-polymind)
