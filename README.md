# TrustHire

> **TrustHire** is a multimodal AI-powered recruitment fraud detection and interview verification platform designed to identify fake job postings, verify recruiter and company legitimacy, detect salary anomalies, and prevent deepfake-based interview scams.

## Overview

TrustHire aims to improve trust in online recruitment by combining Natural Language Processing (NLP), company and recruiter verification, cross-platform consistency analysis, fraud pattern detection, and real-time interview authenticity verification into a single explainable trust scoring system.

A major objective of this project is the creation of a **large-scale Indian Recruitment Fraud Dataset**, addressing the lack of Indian-centric datasets for fake job detection.

---

## Objectives

- Detect fraudulent job postings using NLP.
- Verify recruiter legitimacy through email, LinkedIn, and domain analysis.
- Verify company authenticity using official records and web presence.
- Detect salary and benefits anomalies.
- Identify common recruitment scam patterns.
- Cross-check job postings across multiple platforms.
- Detect deepfake interviews using video and audio analysis.
- Generate an explainable Trust Score for every recruitment process.
- Build and publish an Indian-centric recruitment fraud dataset.

---

## Core Modules

### Job Posting Analysis
- Text preprocessing
- Scam keyword detection
- Semantic analysis
- NLP-based classification

### Recruiter Verification
- Email domain verification
- LinkedIn profile validation
- Portfolio verification
- Domain reputation analysis

### Company Verification
- MCA registration
- GST verification
- Website validation
- LinkedIn company page
- Glassdoor presence

### Salary & Benefits Analysis
- Salary anomaly detection
- Benefits realism
- Experience vs compensation analysis

### Fraud Pattern Detection
- Registration fee detection
- Training/security deposit detection
- Urgency language
- WhatsApp/Telegram recruitment scams
- Bond and consultancy fee detection

### Cross-Platform Consistency
- LinkedIn
- Naukri
- Wellfound
- Company Careers Page

### Interview Verification (Deepfake Detection)
- Video deepfake detection
- Audio deepfake detection
- Face liveness detection
- Lip-sync verification
- Voice verification
- Face identity verification
- Multimodal trust scoring

### Explainability
- SHAP
- LIME
- Human-readable fraud explanations

---

## Dataset Goals

The project includes the creation of a **large-scale Indian Recruitment Fraud Dataset** containing:

- Job posting information
- Recruiter metadata
- Company metadata
- Salary details
- Fraud indicators
- Cross-platform verification
- Recruiter legitimacy features
- Company legitimacy features
- Interview metadata
- Deepfake labels
- Evidence-backed annotations

### Labels

- Real
- Fake
- Suspicious

---

## Tech Stack

**Backend**
- Python
- FastAPI

**Frontend**
- React
- TypeScript

**Machine Learning**
- PyTorch
- Scikit-learn
- XGBoost
- Hugging Face Transformers

**NLP**
- spaCy
- NLTK
- Sentence Transformers

**Web Scraping**
- Playwright
- Scrapy
- BeautifulSoup

**Deepfake Detection**
- OpenCV
- MediaPipe
- Whisper
- Face Recognition
- Speaker Verification Models

**Explainability**
- SHAP
- LIME

---

## Project Structure

```text
trust-hire/
├── backend/
├── frontend/
├── dataset/
├── models/
│   ├── nlp/
│   ├── recruiter_verification/
│   ├── company_verification/
│   ├── salary_analysis/
│   ├── fraud_detection/
│   ├── cross_platform/
│   └── deepfake_detection/
├── interview_verification/
├── verification/
├── pipelines/
├── configs/
├── docs/
├── research/
├── notebooks/
├── scripts/
├── results/
├── logs/
└── README.md
```

---

## Expected Contributions

- Indian-centric fake job posting dataset
- Multimodal recruitment fraud detection framework
- Recruiter legitimacy verification
- Company authenticity verification
- Salary anomaly detection
- Cross-platform job validation
- Deepfake interview detection
- Explainable AI-based recruitment trust scoring

---

## Vision

TrustHire aims to become an end-to-end recruitment trust platform that protects job seekers and organizations from recruitment fraud through intelligent verification, multimodal AI, and explainable risk assessment while contributing open research datasets and reproducible methodologies to the research community.