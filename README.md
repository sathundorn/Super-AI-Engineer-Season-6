# 🤖 Super AI Engineer Season 6 - Mini Hackathons

This repository contains my submissions for the mini-hackathons in the **Super AI Engineer Season 6** program. The projects cover various domains of Artificial Intelligence, including Data Storytelling, Computer Vision (OCR), Natural Language Processing (RAG), and Machine Learning.

---

## 📊 Hackathon 1: Data Storytelling - From Data to Insight
**File:** `601402_mini_Hackathon_Form_Data_to_Insight.ipynb`

**Project Overview:**
The objective of this hackathon is to leverage Open Data for analytical insights. The analysis involves Data Preparation, Exploratory Data Analysis (EDA), and Insight Discovery.

- **Dataset:** Dataset 2 - Fire statistics in Thailand 2019 (สถิติการเกิดอัคคีภัยในประเทศไทย ปีพ.ศ. 2562 พร้อมข้อมูลความเสียหาย)
- **Deliverables:** A complete Data Storytelling Jupyter Notebook and a 1-minute video presentation summarizing the context, key insights, and actionable takeaways.

---

## 📝 Hackathon 2: Thai Election OCR (Form สส.6/1)
**File:** `Hackaton2_601402.ipynb`

**Project Overview:**
A computer vision and OCR challenge focused on extracting structured voting data from scanned Thai election result documents (Form สส.6/1) from the 2026 Thai general election. 

- **Task:** - Locate the correct row for each pre-filled political party in the voting tables.
  - Extract the corresponding vote counts from PNG scans.
  - Convert all extracted numbers into Arabic digits (0-9).
- **Approach:** This is a test-set-only competition with no training data. The pipeline focuses on prompt engineering, post-processing, and utilizing existing Vision LLMs / OCR APIs.

---

## 🛒 Hackathon 3: FahMai Store RAG System
**File:** `Hackaton3_601402.ipynb`

**Project Overview:**
Building a Retrieval-Augmented Generation (RAG) system for "FahMai" (ฟ้าใหม่), a fictional Thai electronics store. The system is designed to accurately answer 100 multiple-choice questions based on the store's knowledge base (product pages, policies, and store information).

- **Task:** Predict the correct choice among 10 options, which include content-specific answers, "No data available," or "Irrelevant question."
- **Allowed Thai LLMs:** - OpenThaiGPT-ThaiLLM-8B-instruct-v7.2
  - Pathumma-ThaiLLM-qwen3-8b-think-3.0.0
  - Typhoon-S-ThaiLLM-8B-Instruct
  - THaLLE-0.2-ThaiLLM-8b-fa

---

## 🧠 Hackathon 4: Applied Machine Learning & Signal Processing
This hackathon consists of three distinct classification and prediction tasks:

1. **House Recognition (Binary Classification)**
   - **File:** `601402_สรรสร_HouseRecognition.ipynb`
   - **Task:** Classify whether a given image contains a house (1) or not (0).
2. **Heart Disease Prediction**
   - **File:** `601402_Heartipynb.ipynb`
   - **Task:** Predictive modeling to determine the likelihood of heart disease based on medical data.
3. **Sleep Stage Classification**
   - **File:** `601402_sleep.ipynb`
   - **Task:** Signal processing and classification to determine different sleep stages from physiological signals.

---
**Author:** Sathundorn Saiaut (Super AI Engineer Season 6 Participant)
