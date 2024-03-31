---
layout: default
title: ComfyUI
parent: Tools
grand_parent: Building Blocks
nav_order: 2
has_children: false
---


### Download
[ComfyUI](https://github.com/comfyanonymous/ComfyUI){:target="_blank"}


### Install
```
git clone https://github.com/comfyanonymous/ComfyUI.git
cd ComfyUI
python -m venv venv
source venv/bin/activate
pip install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu121
pip install -r requirements.txt
python main.py
```

### Install ComfyUI Manager
```
cd ComfyUI/custom_nodes
git clone https://github.com/ltdrdata/ComfyUI-Manager.git
```
Restart ComfyUI



