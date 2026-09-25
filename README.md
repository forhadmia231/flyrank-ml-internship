# 🚀 FlyRank Machine Learning Internship

## Applied Search Intelligence: Google Search Ranking & Discoverability

This repository contains my completed work from the **Machine Learning Internship Program at FlyRank.ai**.

Over the course of the internship, I worked through an end-to-end machine learning workflow using anonymized real-world search data — from research question development and data understanding to feature analysis, modeling, validation, actionable recommendations, and a final capstone.

The internship helped me strengthen my practical understanding of Machine Learning, Data Analysis, model evaluation, reproducibility, and communicating ML results for real-world decision-making.

---

## 👨‍💻 Intern

**Md Forhad Mia**  
Machine Learning Engineer  

🎓 B.Sc. in Computer Science & Engineering  
**Presidency University — 2026**

### Core Skills

`Python` `SQL` `Pandas` `NumPy` `Scikit-learn` `Matplotlib` `Jupyter Notebook` `Git` `GitHub`

---

# 🎯 Internship Focus

The main focus of this internship was **Applied Search Intelligence** — using Machine Learning and data analysis to understand search performance and identify useful content opportunities.

Rather than focusing only on model accuracy, the internship emphasized the complete ML workflow:

```text
Problem Framing
      ↓
Data Understanding
      ↓
Data Cleaning
      ↓
Feature Analysis
      ↓
Leakage Checking
      ↓
Baseline Model
      ↓
Machine Learning Model
      ↓
Validation & Evaluation
      ↓
Failure Analysis
      ↓
Actionable Recommendations
      ↓
Human Review
      ↓
Capstone & Research Communication
```

---

# 📅 8-Week Internship Journey

## Week 1 — Research Question & Data Discovery

📓 `w01_research_question.ipynb`

I started by exploring the dataset and developing a clear research question.

The focus was on understanding:

- What problem I wanted to investigate
- What the available data could actually support
- Which variables might be useful
- How to turn an initial idea into a measurable ML problem

---

## Week 2 — Machine Learning Task Framing

📓 `w02_ml_task_framing.ipynb`

I converted the research question into a structured Machine Learning task.

This included thinking about:

- The prediction/decision target
- Inputs and features
- Expected outputs
- Evaluation strategy
- How the model could support a real decision

This week helped me understand that a good ML project starts with **clear problem framing**, not simply choosing an algorithm.

---

## Week 3 — Data Contract & Leakage Analysis

📓 `w03_data_contract.ipynb`  
📓 `w03_feature_leakage_check.ipynb`

I worked on understanding the structure and limitations of the data before modeling.

Key areas included:

- Understanding feature definitions
- Checking data quality
- Identifying potentially unsafe features
- Detecting feature leakage
- Separating information that would and would not be available at prediction time

This stage reinforced the importance of building models on valid information rather than accidentally giving them access to future or target-related data.

---

## Week 4 — Signal Audit & Baseline

📓 `w04_signal_audit.ipynb`  
📓 `w04_baseline_score.ipynb`

I investigated which features contained useful signals and established a baseline for comparison.

The work included:

- Feature exploration
- Signal analysis
- Building a transparent baseline
- Creating a reference point for later models

The baseline provided a simple benchmark so that more complex models could be evaluated against something meaningful.

---

## Week 5 — Machine Learning Model

📓 `w05_model.ipynb`

I moved from baseline analysis to building and evaluating Machine Learning models.

The reference workflow included models such as:

- Logistic Regression
- Decision Tree
- Random Forest

I worked on:

- Preparing model features
- Training models
- Evaluating predictions
- Comparing model performance
- Understanding model outputs

The objective was not simply to obtain a high score, but to determine whether the learned model provided useful improvement over the baseline.

---

## Week 6 — Validation Audit

📓 `w06_validation_audit.ipynb`

This week focused on testing whether the model results were genuinely trustworthy.

I worked with concepts including:

- Time-aware validation
- Data leakage checks
- Failure examples
- Model limitations
- Evaluation beyond a single metric

This was one of the most important lessons from the internship:

> A strong model score means very little if the validation process does not represent how the model will actually be used.

---

## Week 7 — Action Playbook

📓 `w07_action_playbook.ipynb`

I transformed validated model outputs into an actionable content decision framework.

The playbook included:

- Ranked actions
- Reason codes
- Archetype → action mapping
- Decay / refresh insights
- Intended use
- Human-review rules
- Cost/value considerations
- Monitoring triggers
- Retraining considerations
- Cases that should **not** be automated

The notebook also exports reusable outputs to:

```text
work/outputs/
```

This stage helped bridge the gap between **Machine Learning predictions and practical decision-making**.

---

## Week 8 — Capstone

📓 `capstone.ipynb`

The final stage brought the internship work together into a complete capstone.

The capstone connects the full workflow:

```text
Research Question
        ↓
Data
        ↓
Features
        ↓
Baseline
        ↓
Model
        ↓
Validation
        ↓
Interpretation
        ↓
Recommendations
        ↓
Limitations
        ↓
Reproducible Results
```

The goal was to communicate not only what the model produced, but also:

- Why the problem matters
- How the analysis was performed
- What the results mean
- Where the model can fail
- What should remain under human review
- How the work can be reproduced

---

# 📓 Internship Notebooks

| Week | Assignment | Notebook | Open |
|---|---|---|---|
| 1 | ML-02 | `w01_research_question` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/forhadmia231/flyrank-ml-internship/blob/main/work/notebooks/w01_research_question.ipynb?flush_cache=true) |
| 2 | ML-03 | `w02_ml_task_framing` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/forhadmia231/flyrank-ml-internship/blob/main/work/notebooks/w02_ml_task_framing.ipynb?flush_cache=true) |
| 3 | ML-04 | `w03_data_contract` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/forhadmia231/flyrank-ml-internship/blob/main/work/notebooks/w03_data_contract.ipynb?flush_cache=true) |
| 3 | ML-05 | `w03_feature_leakage_check` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/forhadmia231/flyrank-ml-internship/blob/main/work/notebooks/w03_feature_leakage_check.ipynb?flush_cache=true) |
| 4 | ML-06 | `w04_signal_audit` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/forhadmia231/flyrank-ml-internship/blob/main/work/notebooks/w04_signal_audit.ipynb?flush_cache=true) |
| 4 | ML-07 | `w04_baseline_score` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/forhadmia231/flyrank-ml-internship/blob/main/work/notebooks/w04_baseline_score.ipynb?flush_cache=true) |
| 5 | ML-08 | `w05_model` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/forhadmia231/flyrank-ml-internship/blob/main/work/notebooks/w05_model.ipynb?flush_cache=true) |
| 6 | ML-09 | `w06_validation_audit` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/forhadmia231/flyrank-ml-internship/blob/main/work/notebooks/w06_validation_audit.ipynb?flush_cache=true) |
| 7 | ML-10 | `w07_action_playbook` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/forhadmia231/flyrank-ml-internship/blob/main/work/notebooks/w07_action_playbook.ipynb?flush_cache=true) |
| 8 | ML-11 | `capstone` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/forhadmia231/flyrank-ml-internship/blob/main/work/notebooks/capstone.ipynb?flush_cache=true) |

---

# 🧠 Machine Learning Pipeline

The repository includes a reference ML pipeline:

```text
01_prepare_features.py
        ↓
02_baseline_score.py
        ↓
03_train_model.py
        ↓
04_evaluate_and_export.py
        ↓
05_build_pdf_report.py
```

### Pipeline Responsibilities

**01 — Prepare Features**  
Cleans the data, prepares the feature vector, and defines the target.

**02 — Baseline Score**  
Creates a transparent rule-based baseline.

**03 — Train Model**  
Trains Machine Learning models including Logistic Regression, Decision Tree, and Random Forest.

**04 — Evaluate & Export**  
Evaluates model performance and generates ranked outputs, charts, and reports.

**05 — Build Report**  
Creates a shareable summary of the analysis.

---

# 📂 Repository Structure

```text
flyrank-ml-internship/
│
├── notebooks/
│   └── First-look and introductory notebooks
│
├── work/
│   ├── notebooks/
│   │   ├── w01_research_question.ipynb
│   │   ├── w02_ml_task_framing.ipynb
│   │   ├── w03_data_contract.ipynb
│   │   ├── w03_feature_leakage_check.ipynb
│   │   ├── w04_signal_audit.ipynb
│   │   ├── w04_baseline_score.ipynb
│   │   ├── w05_model.ipynb
│   │   ├── w06_validation_audit.ipynb
│   │   ├── w07_action_playbook.ipynb
│   │   └── capstone.ipynb
│   │
│   └── outputs/
│
├── scripts/
├── outputs/
├── docs/
├── data/
└── README.md
```

---

# 📊 Key Learning Outcomes

Through this internship, I developed a stronger practical understanding of:

- Machine Learning problem framing
- Data exploration and preprocessing
- Feature engineering
- Data leakage prevention
- Baseline development
- Model training
- Model comparison
- Time-aware validation
- Failure analysis
- Model limitations
- Ranked ML recommendations
- Human-in-the-loop decision making
- Monitoring and retraining considerations
- Reproducible ML workflows
- Technical documentation
- Git & GitHub workflows
- Communicating Machine Learning results

---

# 🔐 Data Safety

The repository works with an **anonymized** slice of FlyRank search data.

No private client names, domains, URLs, titles, keywords, credentials, or other confidential client information should be committed to this repository.

Results should be interpreted as:

**Observed • Measured • Directional • Decision-Support**

rather than claims about predicting Google's algorithm.

---

# 💡 Biggest Takeaway

The biggest lesson I gained from this internship is that Machine Learning is much more than training a model.

A useful ML workflow requires:

**Good problem framing + reliable data + leakage prevention + meaningful validation + explainable outputs + human judgment.**

A model should support better decisions — not replace careful reasoning.

---

# 🛠️ Technologies Used

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="45" alt="Python"/>
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" height="45" alt="Pandas"/>
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" height="45" alt="NumPy"/>
  &nbsp;&nbsp;
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" height="45" alt="Scikit-learn"/>
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" height="45" alt="Jupyter"/>
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="45" alt="Git"/>
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="45" alt="GitHub"/>
</p>

---

# 📬 Connect With Me

**Md Forhad Mia**

Machine Learning Engineer

📧 Email: **forhadhossain1595@gmail.com**

🔗 GitHub: **@forhadmia231**

---

<p align="center">
  <b>From data → model → validation → action 🚀</b>
</p>

<p align="center">
  Completed as part of the FlyRank Machine Learning Internship Program.
</p>
