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
- Designed and implemented a **production MIP scheduler** to assign field representatives to retail locations across regions and programs, maximizing predicted sales under complex operational constraints.
- Deployed **HiGHS** as the primary MIP solver, with support for **CBC**, **GLPK**, and **SCIP**; tuned solver parameters including time limits, optimality gap tolerance, parallel threads, and MIP heuristics for large instances.
- Implemented an **adaptive solving strategy** that automatically selects standard optimization vs. **binary-search constraint programming** based on problem size, finding maximum feasible sales targets for large rep/location sets.
- Prototyped an alternative **constraint programming** formulation using **Google OR-Tools CP-SAT** for experimentation and model validation.
- Built an **ML pipeline** to predict representative performance using **XGBoost**, **LightGBM**, and **Random Forest**, with automatic model selection, **Optuna** hyperparameter tuning, temporal train/test splits, and **quantile regression** models (Q10/Q90) for prediction intervals.
- Engineered features from historical shift data, Canadian census demographics, holiday calendars, weather data (Open-Meteo), and rolling/lag statistics; applied sample weighting for low/high performers and recent data.
- Evaluated models with **SHAP** analysis and feature importance; classified representatives by performance consistency to support estimator selection and error analysis.
- Integrated **Google Maps Distance Matrix API** for travel-time and proximity calculations between representative home locations and retail sites, with caching to reduce API costs.
- Used **OpenAI structured-output parsing** to extract location availability and capacity from unstructured notes, enabling deterministic optimization inputs.
- Deployed a **cloud-native AWS architecture**: **API Gateway**, **Lambda** (trigger and ML inference), **Step Functions** orchestration, **AWS Batch** (Dockerized EC2 jobs), **S3** (models, configs, results), **ECR**, **RDS** (MySQL), and **VPC endpoints** for private connectivity.
- Containerized the optimization workflow with **Docker** and automated image builds via **AWS CodeBuild**; provisioned infrastructure with **AWS CDK**.
- Implemented database integration via **SQLAlchemy** and stored procedures for scheduling data ingestion; persisted optimized schedules.
- Developed **Streamlit** dashboards for backtesting, performance-estimator comparison, and weekly APH analysis to validate models before production deployment.
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
