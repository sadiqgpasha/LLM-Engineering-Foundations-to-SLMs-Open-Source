<p align = "center" draggable=”false” ><img src="https://github.com/AI-Maker-Space/LLM-Dev-101/assets/37101144/d1343317-fa2f-41e1-8af1-1dbb18399719" 
     width="200px"
     height="auto"/>
</p>

<h1 align="center" id="heading"> 🚇 Session 7: Fine-Tuning</h1>

### [Quicklinks](https://github.com/AI-Maker-Space/LLM-Engineering-Foundations-to-SLMs/tree/main/00_AIM_Quicklinks)

| 📰 Session Sheet | 📽️ YouTube Video  | 🖼️ Slides      | 👨‍💻 Repo         |
|:-----------------|:-----------------|:-----------------|:-----------------|
| [Session 7: Fine-Tuning ](https://www.notion.so/Session-7-Fine-Tuning-1a7cd547af3d80e3adedd44ef63ac992) | [07: Fine-Tuning](https://www.youtube.com/watch?v=ELu2dy2Iccs&ab_channel=AIMakerspace) |  [Session 7: Fine-Tuning](https://www.canva.com/design/DAGY7ZxFsRU/wzpT21_Ub_a3RAo3-HVvPQ/view?utm_content=DAGY7ZxFsRU&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hcadf98dde7) | You Are Here! | 

### Assignment: 

Today's assignments are available in Colab:
- Assignment #1: 
    - [Assignment](https://colab.research.google.com/drive/18KDy41LCsTKpg6M03A94VkGqRuVJx4yA?usp=sharing)
    - [Hardmode Assignment](https://colab.research.google.com/drive/1lXa2jU2_7aEduHI5x2TWZ5x3VawLKSKa?usp=sharing)

1. Breakout Room #1:
  - Task #1: Loading the Model
    - 👪❓ Discussion Question #1
    - ❓ Question #1
    - ❓ Question #2
2. Breakout Room #2:
  - Task #2: Data and Data Prep.
    - 🏗️ Activity #1
  - Task #3: Setting up PEFT LoRA
    - ❓ Question #3
  - Task #4: Training the Model
    - ❓ Question #4
    - ❓ Question #5
  - Task #5: Share Your Model!
    - ❓ Question #6
   
### Hardmode:

Take the [base](https://huggingface.co/meta-llama/Llama-3.1-8B) Llama 3.1 8B model and instruction-tune it using TRL on [this](https://huggingface.co/datasets/yahma/alpaca-cleaned) instruction following dataset. 

Evaluate your final model using the Eleuther AI's [`lm-evaluation-harness`](https://github.com/EleutherAI/lm-evaluation-harness/tree/main) on the [`IFEval`](https://github.com/EleutherAI/lm-evaluation-harness/blob/main/lm_eval/tasks/ifeval/README.md) task.

Report the baseline Llama 3.1 8B model's performance and your model's performance, then compare and contrast your results with Llama 3.1 8B Instruct.

> NOTE: This will consume a large volume of compute credits - and take a long time! Only embark on this journey if you really want to get deep into the weeds!
