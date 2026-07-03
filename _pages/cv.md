---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[**Download my CV (PDF)**](/files/CV_Zidan.pdf)

Education
======
* B.S. in Computer Science & Engineering, American International University Bangladesh (AIUB), 2020–2024, CGPA 3.77/4.00
  * Thesis: "A Study on the Use of Machine Learning Algorithms for Predicting Mental Health Conditions" (completed, unpublished)

Work experience
======
* Jan 2024 – Present: Machine Learning Engineer, Nasir Syntax Solution Limited
  * Designed and shipped production RAG and agentic LLM systems, reducing retrieval latency by 40%
  * Fine-tuned and quantized LLMs with LoRA/QLoRA, achieving 60% reduction in memory footprint for edge deployment
* Apr 2025 – Nov 2025: AI Developer (Part-time, Remote), GradMate.ai
  * Built agentic RAG systems and multi-step AI workflows using LangChain and Groq
* May 2025 – Feb 2026: AI Engineer (Contractual, Remote), Ambitionix
  * Fine-tuned LLMs for domain-specific tasks and deployed agents and APIs to production
* Oct 2023 – Dec 2023: Machine Learning Intern, Nasir Syntax Solution Limited
  * Investigated personalized recommendation systems, chatbots, and text generation using LLMs and computer vision

Skills
======
* Programming: Python, R
* Frameworks: PyTorch, TensorFlow, Keras, LangChain, Groq, FastAPI, FAISS, Hugging Face, ONNX
* Tools: Docker, MLflow, Kubernetes, GitHub, LoRA/QLoRA
* Databases: SQL, MongoDB

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and leadership
======
* Research collaboration with AIUB faculty on COVID-19 vaccine adverse event modeling (VAERS paper, under review)
