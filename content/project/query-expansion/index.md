---
title: Query expansion
subtitle: 01S
date: 2019-06-01T14:55:10.605Z
draft: false
featured: true
tags:
  - semantic search
  - word sense disambiguation
  - word embeddings
  - Aho–Corasick algorithm
  - NLTK
  - fastText
  - FastAPI
  - Solr
categories:
  - Work projects
links: []
image:
  filename: ""
  focal_point: Smart
  preview_only: false
---
As part of a search engine for institutional documents, I designed and developed a fast pipeline for the interpretation and expansion of the user query. In the query, named entities, dates, domain terms and complex terms are detected. Common terms are enriched with their most inherent synonyms, estimated on the basis of context: I conceived a simple Word sense disambiguation algorithm, which combines knowledge from Wordnet and word embeddings. **The pipeline simplifies and makes the search on the site more effective, concretely increasing transparency**.

*Used by: Comune di Milano, Comune di Palermo, Regione Umbria, Regione Siciliana, Polizia Municipale di Roma Capitale*