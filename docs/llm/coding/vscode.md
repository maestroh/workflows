---
layout: default
title: Setup VS Code
parent: Coding
grand_parent: LLM
nav_order: 3
has_children: false
---

### setup llama.cpp
```
git clone https://github.com/ggerganov/llama.cpp
cd llama.cpp
make LLAMA_CUBLAS=1 
python3 -m pip install -r requirements.txt
.\server -c 4096 --host 0.0.0.0 -t 16 -ngl 25 --mlock -m models/{your model}

```

### Models
Download the model you'd like to use and place it in the `llama.cpp/models` directory

[DeepseekCoder](https://www.reddit.com/r/LocalLLaMA/comments/1acjpn7/deepseekcoder_when_the_large_language_model_meets/){:target="_blank"}

[Additional Models](https://continue.dev/docs/model-setup/select-model)

### Setup Continue in VS Code

1. [Install](https://continue.dev/docs/quickstart) the Continue extension from the Visual Studio marketplace 
1. Select a provider [Select a Provider](https://continue.dev/docs/model-setup/select-provider)
1. Setup your model 