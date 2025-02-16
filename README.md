# LLM-FineTuning-Agent
This repo includes my initial work on understanding fine-tuning LLM models and preparing an AI agent.

__Task 1:__  Do the exercise given in the [link](https://huggingface.co/blog/sdiazlor/fine-tune-deepseek-with-a-synthetic-reasoning-data) and share your code.

- The first step is to create synthetic data to fine-tune LLMs. I will work on the steps provided in the [link](https://huggingface.co/blog/synthetic-data-generator).

  "
  Getting started with our git and git-lfs interface

- You can create a repository from the CLI (skip if you created a repo from the website)

```$pip install huggingface_hub
#You already have it if you installed transformers or datasets

$huggingface-cli login
#Log in using a token from huggingface.co/settings/tokens
#Create a model or dataset repo from the CLI if needed
```

Clone your model, dataset or Space locally

```#Make sure you have git-lfs installed
#(https://git-lfs.github.com)
$git lfs install
$git clone https://huggingface.co/username/repo_name
```

Then add, commit and push any file you want, including large files

#save files via `.save_pretrained()` or move them here
$git add .
$git commit -m "commit from $USER"
$git push






