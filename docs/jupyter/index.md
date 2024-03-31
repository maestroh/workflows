---
layout: default
title: Jupyter Notbooks
nav_order: 4
has_children: true
has_toc: false
---


## Setup a new Jupyter Notebook
```
python3 -m venv myenv
source myenv/bin/activate
pip install jupyter notebook ipykernel
python -m ipykernel install --user --name=myenv
jupyter notebook
```
