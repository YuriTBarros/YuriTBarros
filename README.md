<h1 align="center"> Hello, I'm Yuri T. de Barros  👋</h1>

<h3 align="center">Mechanical Engineer & AI/ML Integration Specialist</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Mechanical%20Engineering-B.S.-blue?style=flat-square" alt="Mechanical Engineering">
  <img src="https://img.shields.io/badge/ML%20Engineering-Postgrad-green?style=flat-square" alt="ML Engineering">
</p>

---

### 🚀 About Me

I operate at the intersection of traditional design and build industry and advanced data science and AI operations. I maintain core mechanical engineering systems while simultaneously leading corporate AI/ML implementations, and automated pipeline workflows with AI.

* 🤖 **AI Strategy & Culture:** Contributing to corporate AI committees, establishing governance, creating ethical frameworks, and training teams to embrace responsible AI adoption.
* ⚙️ **Intelligent Automation:** Building custom AI agents and low-code/no-code environments within the Microsoft Power Platform to streamline engineering workflows.
* 📈 **MLOps & Production Architecture:** Designing, deploying, and tracking scalable machine learning models, automated feature stores, and comprehensive logging infrastructure.
* 🏢 **Mechanical Design Expertise:** Leveraging deep domain knowledge in HVAC, plant utilities, industrial refrigeration, plumbing, and fire protection systems.

---

### 🛠️ Tech Stack & Skills

<table>
  <tr>
    <td valign="top" width="50%">
      <strong>🤖 Data Science & MLOps</strong><br />
      • <b>Languages:</b> Python, SQL<br />
      • <b>Frameworks:</b> Scikit-Learn, TensorFlow, Keras, Optuna<br />
      • <b>Feature Store & Ingestion:</b> Feast, Pandas, Parquet Engine<br />
      • <b>MLOps & Infra:</b> MLflow, Docker Compose, GitHub Actions (CI/CD)<br />
      • <b>Monitoring & Logs:</b> Prometheus, Grafana, Loki<br />
      • <b>Automation:</b> n8n Workflows, MS Power Platform, AI Agents
    </td>
    <td valign="top" width="50%">
      <strong>⚙️ Mechanical Engineering</strong><br />
      • <b>Core Fields:</b> Thermodynamics, Fluid Dynamics, Heat Transfer<br />
      • <b>Systems:</b> Industrial HVAC, Plant Utilities, Fire Suppression, Plumbing<br />
      • <b>CAD/BIM Tools:</b> AutoCAD, Revit<br />
      • <b>Compliance:</b> Code Review, Mass Energy Balance, Mechanical Schedules
    </td>
  </tr>
</table>

---

### 🛠️ Featured Engineering & Machine Learning Projects

#### 🏫 1. [Datathon Passos Mágicos — Student Dropout Prediction](https://github.com/YuriTBarros/Datathon-Passos-Magicos)
* **What it does:** An enterprise-grade MLOps platform built to predict student dropout and academic lag risks using an event-driven feature store architecture, automated tuning pipelines, and full-stack container observability.
* **Tech Stack:** `Python` | `Feast (Feature Store)` | `FastAPI` | `Scikit-Learn` | `Optuna` | `MLflow` | `Docker Compose` | `Prometheus` | `Grafana` | `Loki`
* **Key MLOps Highlights:**
  * **Feature Governance:** Configured a centralized Feature Store using Feast for historical training extractions and incremental materialization to an online storage database, enabling low-latency endpoint queries by student identifier (RA).
  * **Automated Tuning & Tracking:** Automated hyperparameter optimization using Optuna, logging experiment artifacts, evaluation metrics, confusion matrices, and feature importance profiles directly to MLflow.
  * **Observability Matrix:** Provisioned a 6-tier Docker Compose monitoring suite connecting Prometheus (scraping FastAPI performance and cAdvisor container footprints) and Loki/Promtail for unified log auditing within live Grafana dashboards.
  * **Drift Detection & Data Buffering:** Engineered a FastAPI endpoint that pipes new data inputs into a local Parquet retraining buffer while executing statistical Population Stability Index (PSI) checks to dynamically capture feature data drift.
* **👥 Team Collaborators:** [@GabrielHgA](https://github.com/GabrielHgA), [@renanvmelo](https://github.com/renanvmelo), [@rodrigodfernandes](https://github.com/rodrigodfernandes)

#### 📈 2. [Stock Price Prediction with LSTM & MLOps](https://github.com/YuriTBarros/Stock-Prediction-MLOps)
* **What it does:** A production time-series prediction ecosystem managing automated model selection, container orchestration, and continuous workflow automation for deep learning architectures.
* **Tech Stack:** `Python` | `TensorFlow/Keras` | `MLflow` | `n8n Workflows` | `FastAPI` | `Docker Compose` | `PostgreSQL` | `yfinance`
* **Key Deep Learning Highlights:**
  * **Neural Network Benchmarking:** Implemented and benchmarked 3 distinct recurrent network architectures (Simple LSTM, Stacked LSTM, and BiLSTM) across an automated 32-combination hyperparameter grid search, achieving a 1.21% MAPE.
  * **Production Workflow Orchestration:** Built 5 automated n8n pipeline routines to control the model lifecycle—governing weekly hyperparameter retraining, daily updates, continuous prediction loops, and 5-minute uptime health sweeps.
  * **Experiment Lineage:** Tracked and recorded 58 distinct model experiments inside MLflow backed by a containerized PostgreSQL instance to guarantee total metric reproducibility and model heritage control.
* **👥 Team Collaborators:** [@GabrielHgA](https://github.com/GabrielHgA), [@renanvmelo](https://github.com/renanvmelo), [@rodrigodfernandes](https://github.com/rodrigodfernandes)
  
#### 📊 3. [B3 Data Pipeline & Automated Cloud Infrastructure](https://github.com/YuriTBarros/data-pipeline-b3)
* **What it does:** An automated cloud data pipeline that harvests real-time financial market metrics from the B3 stock exchange, executing an event-driven serverless transformation lakehouse.
* **Tech Stack:** `AWS (Lambda, Glue, S3, Athena, API Gateway)` | `Terraform (IaC)` | `Python` | `GitHub Actions (CI/CD)` | `Discord Webhooks`
* **Key Cloud Engineering Highlights:**
  * **Infrastructure as Code (IaC):** Modularized and provisioned the entire multi-tiered serverless AWS stack using declarative Terraform scripts, enforcing strict code-defined identity and parameter management.
  * **Serverless Lakehouse ETL:** Developed an event-driven flow where Lambda scrapers output market files to an S3 Raw tier (daily Parquet partitioning), firing internal events to spin up managed AWS Glue jobs for deduplication and cleaning.
  * **Analytical Exposure:** Cataloged metadata downstream to enable rapid ad-hoc queries via Amazon Athena, exposing structured tables to public consumption through an Amazon API Gateway framework.
* **👥 Team Collaborators:** [@GabrielHgA](https://github.com/GabrielHgA), [@renanvmelo](https://github.com/renanvmelo), [@rodrigodfernandes](https://github.com/rodrigodfernandes)

#### 🤖 4. [AWS ML Cost Predictor](https://github.com/YuriTBarros/AWS-ML-Cost-Predictor)
* **What it does:** A microservices application utilizing a trained regression model to isolate and project ongoing multi-region AWS service operations expenses based on asset consumption metrics.
* **Tech Stack:** `Python` | `Flask` | `AWS (Lambda, Glue, CloudWatch)` | `Scikit-Learn` | `Swagger (Flasgger)` | `Chart.js`
* **Key Application Highlights:**
  * **Statistical Exploration:** Investigated historical cloud operations data to address high-skew sparsity distributions and optimized a Random Forest Regressor yielding a 99.89% $R^2$ accuracy score.
  * **API Service Tier:** Wrapped the serialized machine learning model pipeline inside a lightweight Flask framework, compiling scalable cost-projection routing along with automated Swagger UI documentation.
* **👥 Team Collaborators:** [@GabrielHgA](https://github.com/GabrielHgA), [@renanvmelo](https://github.com/renanvmelo), [@rodrigodfernandes](https://github.com/rodrigodfernandes)

#### 🍇 5. [Vitiviniculture API — FastAPI Ecosystem](https://github.com/YuriTBarros/Vitiviniculture-API)
* **What it does:** A resilient RESTful platform designed to scrap public vitiviniculture logs and offer secured, high-availability caching points for analytical ingestion.
* **Tech Stack:** `Python` | `FastAPI` | `SQLite` | `Docker` | `GitHub Actions` | `Render`
* **Key API Highlights:**
  * **Resilient Caching Engine:** Built automated background scrapers that capture Embrapa web indexes to refresh local caches every 10 minutes, securing zero-downtime application dependency.
  * **Access Management & CI/CD:** Hardened data delivery via JWT token authentication schemes and orchestrated production deployments using a strict GitHub Actions syntax for code-quality linting and Docker compilations.
* **👥 Team Collaborators:** [@felippemauricio](https://github.com/felippemauricio), [@IgorComune](https://github.com/IgorComune), [@MariolGotta](https://github.com/MariolGotta)
---

### 🌐 Connect with me:
<p align="left">
<a href="https://www.linkedin.com/in/yuritoledodebarros/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=flat&logo=Linkedin&logoColor=white" style="margin-right: 10px;" /></a>
<a href="https://tbarros.com/" target="_blank"><img src="https://img.shields.io/badge/-WordPress-21759B?style=flat&logo=wordpress&logoColor=white" /></a>
</p>

💡 Deep dive into my mechanical engineering background and industry observations: [<a href="https://tbarros.com/" target="_blank"><img src="https://img.shields.io/badge/-WordPress-21759B?style=flat&logo=wordpress&logoColor=white" /></a>)

### :green_book: Latest Blog Posts (Portuguese)
* [Refrigeração Industrial: Uma Breve Introdução](https://tbarros.com/refrigeracao-industrial/) 
### 📙 Latest Blog Posts (English)
* [Industrial Refrigeration: A Brief Overview](https://tbarros.com/en/industrial-refrigeration/) 
---
