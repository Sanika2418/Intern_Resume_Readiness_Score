# InternResume_Readiness_Scorer

An AI-powered Resume Analysis and Internship Readiness Prediction Platform developed during my AI/ML Internship at Graphura Pvt. Ltd.

## 📌 Project Overview

Graphura Resume Readiness Scorer helps students and freshers evaluate how well their resume aligns with internship requirements.

The system automatically analyzes uploaded resumes, calculates ATS compatibility, evaluates technical skills, predicts internship readiness using Machine Learning models, and provides personalized improvement suggestions.

Unlike traditional resume checkers, this platform combines ATS analysis, skill matching, GitHub portfolio evaluation, and ML-based prediction to generate a comprehensive candidate readiness score.

---

## 🎯 Problem Statement

Many students apply for internships without knowing:

* Whether their resume is ATS-friendly
* If their skills match the target role
* What technical skills are missing
* How strong their portfolio is
* Whether they are internship-ready

As a result, candidates often get rejected before reaching the interview stage.

This project addresses that problem by providing an automated resume evaluation and readiness prediction system.

---

## 💡 Solution

The platform performs:

1. Resume Parsing
2. ATS Analysis
3. Skill Extraction
4. Role-Based Matching
5. GitHub Portfolio Evaluation
6. Machine Learning Prediction
7. Resume Comparison
8. Personalized Suggestions

The final output is a detailed report showing strengths, weaknesses, missing skills, ATS score, and internship readiness percentage.

---

## 🔥 Key Features

### Resume Analysis

* PDF Resume Parsing
* DOCX Resume Parsing
* OCR Support for Scanned Resumes
* Automatic Name Detection
* Email & Phone Extraction

### ATS Evaluation

* Resume Structure Analysis
* Section Validation
* Keyword Detection
* ATS Compatibility Scoring

### Skill Matching

* Technical Skill Extraction
* Role-Based Skill Evaluation
* Missing Skill Identification
* Skill Match Percentage

### Machine Learning Prediction

* Internship Readiness Prediction
* Resume Strength Classification
* Candidate Scoring System

### GitHub Portfolio Analysis

* Repository Evaluation
* Portfolio Consistency Analysis
* Developer Profile Assessment

### Resume Comparison

* Side-by-Side Resume Evaluation
* ATS Score Comparison
* Skill Match Comparison
* Readiness Score Comparison

### History Tracking

* Store Previous Reports
* Track Improvements Over Time

---

## Machine Learning Implementation

### Models Used

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Random Forest Regressor

### Features Used for Prediction

* Skills Detected
* Number of Projects
* Certifications
* GitHub Repository Count
* Resume Completeness
* ATS Score
* Technical Keyword Density
* Target Internship Role

### Prediction Output

The model predicts:

* Internship Readiness Score
* Resume Strength
* Skill Match Level
* Candidate Ranking

---

## ⚙️ System Workflow

```text
Resume Upload
      ↓
Resume Parsing
      ↓
Skill Extraction
      ↓
ATS Analysis
      ↓
Feature Engineering
      ↓
Machine Learning Prediction
      ↓
Readiness Score Generation
      ↓
Suggestions & Feedback
```

---

## 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend

* Flask
* Python

### Database

* MongoDB

### Machine Learning

* Scikit-Learn
* Pandas
* NumPy
* Joblib

### Resume Processing

* pdfplumber
* python-docx
* pytesseract
* pypdfium2

---

## 📊 Dashboard Metrics

The platform generates:

| Metric             | Description                     |
| ------------------ | ------------------------------- |
| ATS Score          | Resume ATS compatibility        |
| Skill Match        | Match with target role          |
| Resume Quality     | Overall resume quality          |
| Completeness Score | Resume section completeness     |
| Readiness Score    | Internship readiness prediction |

---

## 📈 Project Outcomes

* Automated resume evaluation process
* Reduced manual resume screening effort
* Improved candidate awareness of skill gaps
* Generated actionable recommendations
* Provided role-specific internship guidance
* Enabled ATS-friendly resume optimization

---

## 🚀 Future Enhancements

* LinkedIn Profile Analysis
* AI Resume Builder
* AI-Powered Resume Suggestions
* Real-Time Internship Recommendations
* Interview Readiness Assessment
* PDF Report Generation

---

## 👩‍💻 Author

**Sanika Shewale**
MCA | AI/ML Intern | Data Analyst Enthusiast

Developed during internship at **Graphura Pvt. Ltd.**
