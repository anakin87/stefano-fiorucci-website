---
title: Fact Checking 🎸 Rocks!
subtitle: Fact checking baseline combining dense retrieval and textual entailment
date: 2022-09-01T15:45:30.438Z
draft: false
featured: true
tags:
  - fact checking
  - dense passage retrieval
  - textual entailment
  - natural language inference
  - transformers
  - Haystack
  - Faiss
  - Streamlit
  - large language models
categories:
  - Personal projects
links:
  - url: https://huggingface.co/spaces/anakin87/fact-checking-rocks
    name: Demo! (🤗 Spaces)
    icon: hugs
    icon_pack: emoji
  - url: https://github.com/anakin87/fact-checking-rocks
    name: Code
    icon_pack: fab
    icon: github
  - url: https://www.youtube.com/watch?v=bFwOTKXxKZ0
    icon: youtube
    icon_pack: fab
    name: Haystack Project Highlight Presentation      
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
---
This project aims to show that a naive and simple baseline for fact checking can be built by combining dense retrieval and a textual entailment task. In a nutshell, the flow is as follows:

- the user enters a factual statement
- the relevant passages are retrieved from the knowledge base using dense retrieval
- the system computes the text entailment between each relevant passage and the statement, using a Natural Language Inference model
- the entailment scores are aggregated to produce a summary score.

I also added the feature "Explain using a Large Language Model", which is based on prompting google/flan-t5-large!
