---
# ↑ front matter：layout: default 表示套用 _layouts/default.html 這個外框
layout: default
---

## Professional Summary

Results-driven engineer with 5+ years of experience in semiconductor product
integration and test automation. Combines deep expertise in NVM IP
characterization and test program development with a modern AI/ML skill set
spanning LLM applications (RAG, fine-tuning, agents), computer vision, and
predictive modelling. Proven ability to bridge hardware-facing test engineering
with software-driven automation and AI tooling.

## Experience

### Senior Product Integration Engineer — eMemory Technology Inc.
*Mar 2021 – Present*

- Owned end-to-end development and maintenance of Kalos test programs for embedded
  NVM IP products (NeoBit, NeoFuse, NeoPUF), covering functional verification,
  characterization, and spec compliance across multiple process nodes and foundry partners.
- Automated test data extraction, analysis, and reporting pipelines in Python,
  cutting manual post-processing effort by ~60% and standardising outputs across product lines.
- Architected and deployed an internal RAG-based Q&A tool (LangChain + Ollama + LLaMA 3)
  enabling engineers to query product docs and test logs in natural language —
  reducing spec look-up time and onboarding friction for new team members.
- Collaborated with design, layout, and foundry teams to define test specs, perform
  failure analysis, and drive yield improvement initiatives across high-volume production tapeouts.
- Contributed to NLP-based text classification and information extraction tools for
  internal knowledge management, applying prompt engineering and fine-tuning techniques.

### System Development Engineer — Newmax Technology Co., Ltd.
*Apr 2020 – Feb 2021*

- Designed and deployed a factory-floor IIoT monitoring system over OPC-UA, providing
  real-time production visibility and automated anomaly alerts that reduced undetected downtime.
- Conducted exploratory data analysis on production logs to surface bottlenecks;
  insights directly informed process adjustments that improved line throughput.
- Led planning and integration of AMR (autonomous mobile robot) and robotic arm systems
  for a new factory line, reducing manual material-handling headcount requirements.
- Built and maintained the MES server stack — Django back-end, MongoDB, and OPC-UA
  communication layer — supporting live production tracking.

## Projects

### AI Web Assistant
Selenium-powered web scraper paired with an Ollama LLM backend to automatically
extract, summarise, and answer questions about scraped content. Streamlit front-end.
[GitHub](https://github.com/wesleyhuan/Ollama_web_scraper)

### Local AI Agent (RAG over Excel)
Converted tabular Excel data into vector embeddings (mxbai-embed-large) and wired a
local LLaMA 3 model via RAG to answer business questions over the data — no cloud APIs.
[GitHub](https://github.com/wesleyhuan/local_AI_agent)

### Kaggle Competition Solutions
End-to-end ML solutions spanning regression, classification, and feature engineering —
from EDA through model selection and ensembling.
[GitHub](https://github.com/wesleyhuan/kaggle_competition)

### MOS Burger IoT — Predictive Maintenance
Built one-class SVM models on sensor time-series data to predict electrical equipment
failure before it occurred, reducing unplanned downtime on production equipment.

### Kangmei Pharmaceutical — Medical Data Platform
Developed a Django REST server and data pipeline for medical analytics; applied
statistical methods (P-value, correlation analysis) with domain experts to surface
clinically meaningful patterns.

## Education

**M.Eng. Electronics Engineering — Automatic Control** · GPA 3.99
National Cheng Kung University (NCKU) · Sep 2017 – Sep 2019
*Thesis: Construction of a Non-Communicable Disease Risk Prediction Model Using Data Mining Methods*

**B.Eng. Electronics Engineering** · GPA 3.87
National Central University (NCU) · Sep 2013 – Jun 2017

## Technical Skills

- **Programming:** Python (primary), C/C++
- **LLM & AI:** LangChain, Langflow, Ollama, RAG, Prompt Engineering, Fine-tuning, Agents
- **ML / DL:** Keras, TensorFlow, SVM, RNN, ANN, LightGBM, XGBoost, CatBoost
- **Computer Vision:** DINO_V2 (ViT), CNN, YOLO
- **Data & Backend:** Pandas, EDA, Data Mining, Selenium, Django, MongoDB
- **Tools:** Git/GitHub, Jupyter, VS Code, PyCharm, Raspberry Pi

## Languages & Certifications

- **English:** Professional Working Proficiency — TOEIC 905
- **Mandarin Chinese:** Native
- AI Deep Learning Talent Camp, Southern Taiwan Science Park
- Building LLM Applications with Prompt Engineering (NVIDIA)
- Artificial Intelligence Fundamentals (IBM)
