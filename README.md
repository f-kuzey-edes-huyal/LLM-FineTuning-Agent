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

```# Make sure you have git-lfs installed
# (https://git-lfs.github.com)
$ git lfs install
$ git clone https://huggingface.co/username/repo_name
```

Then add, commit and push any file you want, including large files

```
#save files via `.save_pretrained()` or move them here
$ git add .
$ git commit -m "commit from $USER"
$ git push
```

In most cases, if you're using one of the compatible libraries, your repo will then be accessible from code, through its identifier: username/repo_name

For example for a transformers model, anyone can load it with:

```
tokenizer = AutoTokenizer.from_pretrained("username/repo_name")
model = AutoModel.from_pretrained("username/repo_name")
```
"

[How to Fine-Tune LLaMA 3.1 Locally: A Step-by-Step Guide](https://medium.com/@adarsh.ajay/how-to-fine-tune-llama-3-1-locally-a-step-by-step-guide-341de509d64f)

https://www.reddit.com/r/Codeium/comments/1h4jo15/how_to_configure_windsurf_to_use_local_llms_such/


__Notes:__ [windsurf ai](https://codeium.com/windsurf)

