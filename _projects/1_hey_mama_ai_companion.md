---
layout: page
title: Hey Mama! AI companion
description: A fully local, privacy-preserving RAG assistant grounded in 170 clinical guidelines.
img:
importance: 1
category: healthcare
---

**Hey Mama!** is a clinical maternal and postpartum health app affiliated with Hamilton Health Sciences. During my Mitacs Globalink Research Internship at the Flourish Lab at McMaster University, I engineered its AI companion feature.

- **Fully local and privacy-preserving.** The retrieval-augmented generation (RAG) pipeline runs entirely on local infrastructure, so no patient data leaves it.
- **Grounded in clinical guidelines.** Answers are grounded in 170 clinical guidelines.
- **Stack:** LiteParse, ChromaDB, LangChain, Ollama.
- **Evaluation.** I benchmarked LLMs and embedding models, evaluating retrieval across 30 clinician-style questions (87% Hit@5) and comparing inference speed between 1B- and 3B-parameter models.

I presented this work as an oral talk, _Beyond ChatGPT: A Clinical AI That Never Leaves the Building_, to medical students and physicians at McMaster Children's Hospital.
