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

<!-- 時間軸：左側一條線 + 年份節點。每個 .tl-item 是一段經歷 -->
<div class="timeline">

  <div class="tl-item">
    <div class="tl-meta">Mar 2021 – Present</div>
    <h3>Senior Product Integration Engineer — eMemory Technology Inc.</h3>
    <ul>
      <li>Owned end-to-end development and maintenance of Kalos test programs for embedded NVM IP products (NeoBit, NeoFuse, NeoPUF), covering functional verification, characterization, and spec compliance across multiple process nodes and foundry partners.</li>
      <li>Automated test data extraction, analysis, and reporting pipelines in Python, cutting manual post-processing effort by ~60% and standardising outputs across product lines.</li>
      <li>Architected and deployed an internal RAG-based Q&amp;A tool (LangChain + Ollama + LLaMA 3) enabling engineers to query product docs and test logs in natural language — reducing spec look-up time and onboarding friction for new team members.</li>
      <li>Collaborated with design, layout, and foundry teams to define test specs, perform failure analysis, and drive yield improvement initiatives across high-volume production tapeouts.</li>
      <li>Contributed to NLP-based text classification and information extraction tools for internal knowledge management, applying prompt engineering and fine-tuning techniques.</li>
    </ul>
  </div>

  <div class="tl-item">
    <div class="tl-meta">Apr 2020 – Feb 2021</div>
    <h3>System Development Engineer — Newmax Technology Co., Ltd.</h3>
    <ul>
      <li>Designed and deployed a factory-floor IIoT monitoring system over OPC-UA, providing real-time production visibility and automated anomaly alerts that reduced undetected downtime.</li>
      <li>Conducted exploratory data analysis on production logs to surface bottlenecks; insights directly informed process adjustments that improved line throughput.</li>
      <li>Led planning and integration of AMR (autonomous mobile robot) and robotic arm systems for a new factory line, reducing manual material-handling headcount requirements.</li>
      <li>Built and maintained the MES server stack — Django back-end, MongoDB, and OPC-UA communication layer — supporting live production tracking.</li>
    </ul>
  </div>

</div>

## Projects

<!-- 專案卡片：有 GitHub 連結的用 <a> 整張可點，沒有的用 <div> -->
<div class="cards">

  <a class="card" href="https://github.com/wesleyhuan/Ollama_web_scraper">
    <h3>AI Web Assistant</h3>
    <p>Selenium-powered web scraper paired with an Ollama LLM backend to automatically extract, summarise, and answer questions about scraped content. Streamlit front-end.</p>
    <span class="card-link">GitHub →</span>
  </a>

  <a class="card" href="https://github.com/wesleyhuan/local_AI_agent">
    <h3>Local AI Agent (RAG over Excel)</h3>
    <p>Converted tabular Excel data into vector embeddings (mxbai-embed-large) and wired a local LLaMA 3 model via RAG to answer business questions over the data — no cloud APIs.</p>
    <span class="card-link">GitHub →</span>
  </a>

  <a class="card" href="https://github.com/wesleyhuan/kaggle_competition">
    <h3>Kaggle Competition Solutions</h3>
    <p>End-to-end ML solutions spanning regression, classification, and feature engineering — from EDA through model selection and ensembling.</p>
    <span class="card-link">GitHub →</span>
  </a>

  <div class="card">
    <h3>MOS Burger IoT — Predictive Maintenance</h3>
    <p>Built one-class SVM models on sensor time-series data to predict electrical equipment failure before it occurred, reducing unplanned downtime on production equipment.</p>
  </div>

  <div class="card">
    <h3>Kangmei Pharmaceutical — Medical Data Platform</h3>
    <p>Developed a Django REST server and data pipeline for medical analytics; applied statistical methods (P-value, correlation analysis) with domain experts to surface clinically meaningful patterns.</p>
  </div>

</div>

## Education

**M.Eng. Electronics Engineering — Automatic Control** · GPA 3.99
National Cheng Kung University (NCKU) · Sep 2017 – Sep 2019
*Thesis: Construction of a Non-Communicable Disease Risk Prediction Model Using Data Mining Methods*

**B.Eng. Electronics Engineering** · GPA 3.87
National Central University (NCU) · Sep 2013 – Jun 2017

## Technical Skills

<!-- 技能用分組標籤(chip)，比純文字清單好掃讀 -->
<div class="skills">

  <div class="skill-group">
    <h4>Programming</h4>
    <ul class="chips">
      <li>Python</li><li>C/C++</li>
    </ul>
  </div>

  <div class="skill-group">
    <h4>LLM &amp; AI</h4>
    <ul class="chips">
      <li>LangChain</li><li>Langflow</li><li>Ollama</li><li>RAG</li><li>Prompt Engineering</li><li>Fine-tuning</li><li>Agents</li>
    </ul>
  </div>

  <div class="skill-group">
    <h4>ML / DL</h4>
    <ul class="chips">
      <li>Keras</li><li>TensorFlow</li><li>SVM</li><li>RNN</li><li>ANN</li><li>LightGBM</li><li>XGBoost</li><li>CatBoost</li>
    </ul>
  </div>

  <div class="skill-group">
    <h4>Computer Vision</h4>
    <ul class="chips">
      <li>DINO_V2 (ViT)</li><li>CNN</li><li>YOLO</li>
    </ul>
  </div>

  <div class="skill-group">
    <h4>Data &amp; Backend</h4>
    <ul class="chips">
      <li>Pandas</li><li>EDA</li><li>Data Mining</li><li>Selenium</li><li>Django</li><li>MongoDB</li>
    </ul>
  </div>

  <div class="skill-group">
    <h4>Tools</h4>
    <ul class="chips">
      <li>Git/GitHub</li><li>Jupyter</li><li>VS Code</li><li>PyCharm</li><li>Raspberry Pi</li>
    </ul>
  </div>

</div>

## Languages & Certifications

- **English:** Professional Working Proficiency — TOEIC 905
- **Mandarin Chinese:** Native
- AI Deep Learning Talent Camp, Southern Taiwan Science Park
- Building LLM Applications with Prompt Engineering (NVIDIA)
- Artificial Intelligence Fundamentals (IBM)
