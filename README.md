<div align="center">

# Bhushan Sonawane

### Software Developer · Machine Learning · Data Science

Building **software systems, ML applications, and data-driven products** that solve practical problems.

<p>
<a href="https://linkedin.com/in/bhushan-ssh">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://my-portfolio-six-delta-17.vercel.app/">
<img src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=vercel&logoColor=white"/>
</a>
<a href="https://leetcode.com/u/bhushan_ssh/">
<img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white"/>
</a>
<a href="https://www.kaggle.com/bhushanssh">
<img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white"/>
</a>
</p>

</div>

---

## 👨‍💻 About Me

I'm a **B.E. Information Technology** student pursuing a **B.S. in Data Science & Applications from IIT Madras**, with a strong interest in software engineering, machine learning, and data.

I enjoy turning ideas into complete systems:

```text
Problem
   ↓
Data / Requirements
   ↓
Engineering
   ↓
ML / Logic
   ↓
Application
   ↓
Real-World Use
```

### What I enjoy building

* Full-stack and backend applications
* Machine learning and deep learning systems
* Data-driven applications and analytics
* REST APIs and database-backed systems
* Predictive models and ML experiments
* Practical AI applications

---

# 🛠️ Technical Skills

### Languages

<p>
<img src="https://skillicons.dev/icons?i=python,java,mysql" />
</p>

### Web & Backend

<p>
<img src="https://skillicons.dev/icons?i=flask,vue,html,css,git,github" />
</p>

`REST APIs` · `SQLAlchemy` · `Jinja2` · `Bootstrap` · `Pinia` · `Vue Router`

### Machine Learning & Data

<p>
<img src="https://skillicons.dev/icons?i=pytorch,sklearn" />
</p>

`Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `XGBoost` · `CatBoost` · `Streamlit`

### Infrastructure & Databases

`SQLite` · `MySQL` · `Redis` · `Celery` · `Celery Beat`

---

# 🚀 Featured Projects

## 🔗 CareerLink

### Full-Stack Placement & Recruitment Platform

**Vue 3 · Flask · Flask-RESTful · SQLAlchemy · SQLite · Redis · Celery**

A full-stack placement portal designed around real campus-placement workflows, connecting **students, companies, and administrators**.

**What it includes**

* Role-based Student / Company / Admin workflows
* Token-based authentication
* Job and placement-drive management
* Application tracking
* Company approval workflow
* Interview scheduling and feedback
* Admin analytics and platform management
* Asynchronous CSV exports
* Scheduled interview reminders
* Monthly activity reports
* Redis caching and Celery background processing

**Architecture**

```text
Vue 3 + Vite
      │
      ▼
Flask REST API
      │
      ├── SQLAlchemy → SQLite
      │
      └── Redis
            │
            └── Celery / Celery Beat
                    │
                    ├── CSV Exports
                    ├── Scheduled Tasks
                    └── Reports
```

🔗 **Repository:**
https://github.com/bhushan-ssh/CareerLink

---

## 🧠 QuizMaster

### Full-Stack Quiz & Performance Analytics Platform

**Flask · SQLAlchemy · SQLite · Bootstrap · Jinja2 · Matplotlib · Seaborn**

A full-stack web-based quiz platform developed as part of the **BS Degree in Data Science & Applications at IIT Madras**.

### User Features

* Browse subjects, units, and quizzes
* Attempt multiple-choice quizzes
* Instant score calculation
* Performance tracking
* Interactive charts and graphs
* Quiz search
* Profile management

### Admin Features

* Create and manage subjects
* Create and manage units
* Create, edit, and delete quizzes
* Manage questions
* Add hints
* Manage users
* View top scores
* Analyze quiz attempts

### Analytics

* Score trends
* Subject-wise performance
* User rankings
* Pie charts and visualizations

**Repository:**
https://github.com/bhushan-ssh/Quizmaster

---

## 🏭 Uptime

### AI-Powered Predictive Maintenance

**Python · LSTM · Streamlit · Plotly · Machine Learning**

A predictive-maintenance dashboard that analyzes industrial machine telemetry and estimates **Remaining Useful Life (RUL)**.

### Features

* LSTM-based RUL prediction
* Real-time telemetry simulation
* Historical CSV upload
* Failure-mode probability analysis
* Interactive telemetry charts
* RUL gauge
* Vulnerability radar
* XAI-style feature impact visualization

**Pipeline**

```text
Telemetry
    ↓
Preprocessing
    ↓
LSTM Model
    ↓
RUL Prediction
    ↓
Analytics Dashboard
    ↓
Operator Insights
```

🔗 **Repository:**
https://github.com/bhushan-ssh/Uptime

---

## 🤖 Smart MCQ Solver

### Deep Learning & Generative AI

**Python · PyTorch · BERT · BiLSTM · BiGRU · Transformers**

A deep-learning system that predicts and ranks the **top 3 answers** for multiple-choice questions.

Three architectures were evaluated:

```text
BiLSTM
BiGRU + Attention
BERT
      ↓
Model Evaluation
      ↓
Weighted Ensemble
      ↓
Top-3 Answer Ranking
```

### Results

| Model             |      MAP@3 |
| ----------------- | ---------: |
| BiLSTM            |     0.6001 |
| BiGRU + Attention |     0.5944 |
| BERT              |     0.7201 |
| **Ensemble**      | **0.7503** |

The final ensemble improved validation MAP@3 from **0.7201 to 0.7503**.

🔗 **Repository:**
https://github.com/bhushan-ssh/Smart_MCQ_Solver

---

## 🚜 Heavy Equipment Price Prediction

### Machine Learning Regression

**Python · XGBoost · CatBoost · HistGradientBoosting**

A regression pipeline for predicting the selling price of used heavy equipment from historical transaction and equipment data.

### Approach

* Exploratory data analysis
* Missing-value analysis
* Structural missingness handling
* Feature engineering
* Frequency encoding
* Target encoding
* Categorical feature processing
* Log-price modeling
* 5-fold cross-validation
* Ensemble blending

### Model

```text
XGBoost
   +
CatBoost
   +
HistGradientBoosting
        ↓
NNLS Ensemble
        ↓
Price Prediction
```

### Performance

**OOF RMSLE: `0.20217`**

Final ensemble:

* XGBoost → `0.32`
* CatBoost → `0.68`
* HistGradientBoosting → `0.00`

🔗 **Repository:**
https://github.com/bhushan-ssh/Heavy_Equipment_Selling_Price_Prediction

---

## 🚢 Titanic Survival Prediction

### End-to-End Machine Learning Pipeline

**Python · Pandas · Scikit-learn · Streamlit**

A complete classification project covering the full machine-learning workflow from exploratory analysis to deployment.

### Workflow

```text
Dataset
   ↓
EDA
   ↓
Preprocessing
   ↓
Feature Engineering
   ↓
Model Comparison
   ↓
Cross-Validation
   ↓
Hyperparameter Tuning
   ↓
Final Model
   ↓
Streamlit Deployment
```

### Models Evaluated

* Logistic Regression
* SGD Classifier
* Decision Tree
* Random Forest

**Best validation accuracy: `81.56%`**

The final application is deployed using Streamlit.

🔗 **Live Demo:**
https://bhushan-titanic-ml.streamlit.app/

🔗 **Repository:**
https://github.com/bhushan-ssh/Titanic_Survival_Prediction

---

# 🏆 Recognition

<div align="center">

|             🥇            |                 🏆                |                  🥈                  |
| :-----------------------: | :-------------------------------: | :----------------------------------: |
|       **1st Place**       |             **Winner**            |             **Runner-Up**            |
|    SVIT HackVerse 2K26    |          TECHFUSION 2K25          | SND College Project Competition 2024 |
| AI Predictive Maintenance | Micro Project Poster Presentation |          Project Competition         |

</div>

---

# 📈 Problem Solving

### LeetCode

**110+ problems solved**

Focus areas:

`Arrays` · `Strings` · `Hashing` · `Trees` · `Graphs` · `Dynamic Programming` · `Algorithms`

### HackerRank

`SQL Basic` · `SQL Intermediate` · `SQL Advanced` · `Java Basic`

---

# 🔬 Areas of Interest

```text
Software Engineering
        │
        ├── Backend Development
        ├── REST APIs
        ├── Databases
        └── System Architecture

Machine Learning
        │
        ├── Predictive Modeling
        ├── Deep Learning
        ├── NLP
        └── Time-Series

Data Science
        │
        ├── Data Analysis
        ├── Feature Engineering
        ├── Model Evaluation
        └── Data Visualization
```

---

# 📊 GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=bhushan-ssh&show_icons=true&hide_border=true&rank_icon=github&theme=transparent" height="170"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=bhushan-ssh&hide_border=true&theme=transparent" height="170"/>

</div>

<br>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=bhushan-ssh&hide_border=true&area=true&bg_color=00000000" width="95%"/>

</div>

---

# 🌱 Currently Exploring

`Advanced Backend Architecture`

`Machine Learning Systems`

`Advanced SQL & Data Analytics`

`Deep Learning`

`Power BI`

`Competitive Programming`

---

# 🤝 Let's Connect

<div align="center">

I'm interested in **software engineering, machine learning, data science, and building useful products.**

<br>

<a href="mailto:bhushan.sonawane.tech@gmail.com">
<img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://linkedin.com/in/bhushan-ssh">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://my-portfolio-six-delta-17.vercel.app/">
<img src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=vercel&logoColor=white"/>
</a>

</div>

<br>

<div align="center">

### Building with code. Learning with data. Solving real problems.

</div>
