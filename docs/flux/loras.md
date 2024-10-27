---
layout: default
title: Loras
nav_order: 1
has_children: false
parent: Flux
---

```
I've had the best luck with the following: Use controlnet to create an image of your character in flux with multiple views, using a character sheet template. Cut the images out (you can automate this), then train a lora on those. Take this lora, and generate a bunch of random images of the character in all sorts of poses and positions. Then curate and filter THOSE images, and train a new character lora using those. This second lora will be your real one.
You should probably throw in an upscale on the original image, too.
```
Let's break down these steps:
1. Create a character sheet template: I could create a character sheet using this technique: [Flux Consistent Character Sheet](https://www.reddit.com/r/comfyui/comments/1elfcef/flux_consistent_character_sheet/)
1. Using Controlnet: 
1. Train Lora 1:
1. Generate random images: 
1. Train Lora 2: