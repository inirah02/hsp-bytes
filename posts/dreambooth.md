---
title: "Dream Booth Decoded"
description: Fine Tuning Text-to-Image Diffusion Models for Subject-Driven Generation
date: 2021-08-01
tags:
  - researchpapers
layout: layouts/post.njk
---
 
## DreamBooth: Fine Tuning Text-to-Image Diffusion Models for Subject-Driven Generation

As part of White Papers on trending industry topics, we are covering Dream Booth, a large text-to-image model which achieved a remarkable leap in the evolution of AI, enabling high-quality and diverse synthesis of images from a given text prompt.

However, these models lack the ability to mimic the appearance of subjects in a given reference set and synthesize novel renditions of them in different contexts. In this work, we present a new approach for "personalization" of text-to-image diffusion models (specializing them to users' needs). 

Given as input just a few images of a subject, we fine-tune a pretrained text-to-image model (Imagen, although our method is not limited to a specific model) such that it learns to bind a unique identifier with that specific subject. 

Once the subject is embedded in the output domain of the model, the unique identifier can then be used to synthesize fully-novel photorealistic images of the subject contextualized in different scenes. 

By leveraging the semantic prior embedded in the model with a new autogenous class-specific prior preservation loss, our technique enables synthesizing the subject in diverse scenes, poses, views, and lighting conditions that do not appear in the reference images. 

We apply our technique to several previously-unassailable tasks, including subject recontextualization, text-guided view synthesis, appearance modification, and artistic rendering (all while preserving the subject's key features). 

To delve deeper, check out their GitHub Repository and the offical research paper.

PDF: https://paperswithcode.com/paper/dreambooth-fine-tuning-text-to-image

GITHUB: https://dreambooth.github.io/
