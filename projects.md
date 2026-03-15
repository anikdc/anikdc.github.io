---
layout: page
title: Projects
permalink: /projects/
---

Here are the key projects detailed in my latest resume.

---

## [NLP-Driven Commodity Risk Analyzer](https://github.com/anikdc/nlp-risk)
*Python, XGBoost, SHAP, Pandas*

- Engineered an end-to-end ML pipeline with a Bronze→Silver→Gold Data Lake architecture, ingesting 50,000+ Reddit WorldNews headlines and daily WTI Crude Oil prices over an 8-year backtest window (2008–2016).
- Built an NLP scoring engine using Facebook's BART Zero-Shot Classifier to quantify supply chain disruption signals from unstructured text. Designed an Exponential Moving Average (EMA) decay feature to convert sparse news events into continuous risk waveforms for time-series modeling.
- Conducted ablation studies comparing XGBoost regressors with and without NLP features, complemented by SHAP explainability analysis and a Welch's T-Test event study.
- Concluded that general-purpose Zero-Shot models produce indiscriminate severity scores (0.99+ on all pre-filtered text), collapsing feature information content. Identified domain-specific fine-tuning and financial-grade news sourcing as validated next steps.

---

## [AI Agents with RSS](https://github.com/anikdc/RSSAIAgents) *(Ongoing)*
*Python, Scikit-Learn, Streamlit, BeautifulSoup*

- Engineered a multi-agent automated pipeline to ingest real-time RSS feeds, extract raw articles, and autonomously generate comprehensive news briefings.
- Vectorized unstructured news headlines and summaries, applying DBSCAN clustering to mathematically identify high-density, emerging news narratives.
- Built a dynamic data extraction layer using BeautifulSoup4 to scrape full-text content from prioritized topic clusters, bypassing noise and feeding high-signal, structured context into the final generative layer.
- Deployed a narrative synthesis agent to transform aggregated articles into coherent markdown summaries, presented through an interactive Streamlit dashboard.

---

## [Raycasting Engine](https://github.com/anikdc/raycasting)
*Python, PyGame, Vector Math, Trigonometry, Algorithms*

- Engineered a custom pseudo-3D graphics engine from scratch, implementing core volumetric raycasting algorithms and trigonometric transformations to project a 2D array into a fully textured first-person perspective.
- Integrated dynamic FOV scaling, continuous distance scaling and robust 2D boundary collision detection.
- Implemented a synchronous dynamic HUD minimap utilizing 2D spatial transformations to continually translate instantaneous player vectors (coordinates and heading angle) into a live top-down coordinate overlay.
