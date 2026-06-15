---
layout: single
title: "Professional Experience"
permalink: /professionalexperience/
author_profile: true
---

## Data Scientist  
**Yeji Data Lab**, Montreal, QC  
*Sep 2025 – Present*  

### *Project: Automated Workforce Scheduling Optimization for a Major Retail Client*
- Designed and deployed an **end-to-end production MIP scheduler** that assigns field representatives to retail locations, **maximizing** sales volume under complex operational constraints.
- Implemented an adaptive solving strategy shifting between **HiGHS/MIP solvers** and **Google OR-Tools CP-SAT** based on problem scale, reducing large-instance solving time while ensuring model validation.
- Built an **automated ML forecasting pipeline** (**XGBoost**, **LightGBM**, **Random Forest**) with **Optuna** hyperparameter tuning, using **SHAP** analysis to classify representative consistency and **quantile regression** (Q10/Q90) for prediction intervals.
- Engineered features from diverse streams including historical shifts, Canadian census demographics, Open-Meteo weather APIs, and integrated Google Maps Distance Matrix API with custom caching to optimize travel-time constraints while reducing API costs.
- Leveraged **OpenAI** structured-output parsing to transform unstructured operational notes into deterministic data inputs for the optimization engine.
- Architected and provisioned a **cloud-native AWS infrastructure** using **AWS CDK**, **orchestrating ML inference** and **Dockerized Batch jobs** via **Step Functions**, **Lambda**, **ECR**, and **RDS**.
- Implemented database integration via **SQLAlchemy** and stored procedures for scheduling data ingestion; persisted optimized schedules.
- Established **CI** quality gates with **GitHub Actions** and **Ruff** linting/format checks on the production codebase.

### Data Scientist  
**DataSphere Lab | McGill University**, Montreal, QC  
*Jul 2025 – Sep 2025*  
- Analyzed large-scale transactional sales data from [Infasco](https://infasco.com/en/) for industrial demand-planning use cases, including cleaning, anomaly detection, and outlier treatment.  
- Built and evaluated demand forecasting models using `XGBoost` and `LightGBM` to support sales-planning decisions.  
- Engineered temporal and categorical features, tuned models, and assessed performance using `RMSE` and `SMAPE` to improve predictive accuracy.  

## Operations Research Specialist  
**CIRRELT**, Montreal, QC  
*Jan 2021 – Sep 2025*  
- Built a Retrieval-Augmented Generation (RAG) system using `LangChain`, `Azure OpenAI` embeddings, and `FAISS` to retrieve disaster-planning context and answer technical user queries, with fallback search and query-classification logic.
  [▶️ Demo: RAG for ACFs](https://drive.google.com/file/d/1Cjd3syc1J9SaAxIJAySAnkFLeHKD4u0l/view?usp=sharing)
- Developed a `Streamlit` and `LangChain` AI assistant for hospital evacuation planning that interprets free-text queries, extracts planning parameters, and invokes a backend optimization engine. Integrated with `Azure OpenAI` and dynamic user feedback.  
  [▶️ Demo: LLM for ACFs](https://drive.google.com/file/d/1I1Hlg1Rme-twQYp5AfTtrviWK2hv8EQf/view?usp=sharing)
- Designed reinforcement learning models, including `Q-Learning` and `Deep Q-Learning`, combined with `ALNS` to support decision-making under uncertainty in disaster management and resource allocation settings.  
- Developed a `Stochastic Dual Dynamic Programming (SDDP)` algorithm for multi-stage stochastic optimization in casualty response and medical-resource allocation.  
- Applied scenario clustering methods such as `K-means++` and `Self-Organizing Maps`, and benchmarked optimization methods including `Benders decomposition` and `Progressive Hedging` for large-scale planning problems.

<!--
### Data Science Intern (Time Series Forecasting)  
**OneGym (formerly Science and Power Fitness Club)**, Isfahan, Iran  
*Jan 2020 – Aug 2020*  
- Conducted comprehensive exploratory data analysis (EDA) on transactional sales data, identifying trends, anomalies, and outliers to inform predictive modeling.  
- Developed and validated demand forecasting models using machine learning techniques (e.g., XGBoost, LightGBM) to predict sales quantities, optimizing inventory management.  
- Applied feature engineering, including one-hot encoding and temporal feature extraction, to enhance model accuracy, and utilized hyperparameter tuning and statistical evaluation metrics (RMSE, SMAPE).
-->

## Teaching Assistant  
**Concordia University**, Montreal, QC  
*Fall 2024 – Winter 2025*  
- Served as Teaching Assistant for *Scheduling Theory* and *Quantitative Methods in Healthcare Systems*, under the supervision of [Prof. Hossein Hashemi Doulabi](https://www.concordia.ca/faculty/hossein-hashemidoulabi.html), providing support to students in their coursework and projects.

## Lab Demonstrator  
**Concordia University**, Montreal, QC  
*Fall 2024*  
- Assisted [Prof. Gerard Gouw](https://www.concordia.ca/faculty/gerard-gouw.html) in delivering and managing labs for the course *Human Factors Engineering*, ensuring smooth execution of laboratory sessions with more than 30 students.

## Software Trainer  
**FaraDars Educational Institution**, Tehran, Iran  
*Summer 2019*  
- Developed and designed an [online course](https://faradars.org/courses/fvor9802-balancing-in-production-and-assembly-line-using-flexible-line-balancing) titled *How to Balance a Production/Assembly Line using the Flexible Line Balancing (FLB) Software*.  
- Facilitated the enrollment and successful completion of over 900 students in the course.