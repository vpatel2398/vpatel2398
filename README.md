# 🚀 Vivek Patel

### AI/ML Engineer | Healthcare AI · RAG & LLM Systems · Cloud Data Engineering

AI/ML engineer building applied machine learning systems end-to-end — from model training and retrieval pipelines to deployment. My recent work centers on **healthcare AI**: retrieval-augmented generation over clinical data, biomedical NLP, and audio-based diagnostic models, alongside cloud data engineering on Azure and AWS.

I focus on shipping real, deployed projects rather than notebooks that stop at accuracy scores.

---

## 🔬 Core Focus

- **RAG & LLM Systems** — hybrid retrieval, rerankers, biomedical NER, LLM-backed answering
- **Healthcare AI** — clinical document intelligence, voice-based disease detection
- **Applied Deep Learning** — transformer fine-tuning, CNN audio models, computer vision
- **Cloud Data Engineering** — lakehouse / medallion architecture on Azure & AWS

---

## 📌 Featured Projects

### 🏥 Clinical Document Assistant — *Healthcare RAG Pipeline*

A self-hosted retrieval-augmented generation system over FDA drug labels and ClinicalTrials.gov data.

- **Biomedical NER** with PubMedBERT (**0.888 F1**) for entity extraction
- **Hybrid retrieval** combining dense embeddings (`bge-small-en-v1.5`) + BM25, refined with a cross-encoder reranker
- **LLM answering** via Groq integration
- **FastAPI** backend serving the pipeline

### 🧠 Parkinson's Disease Detection from Voice — *Deployed*

Speech-based Parkinson's screening model, rebuilt and deployed on **Hugging Face Spaces**.

- Praat-based acoustic feature extraction
- **Subject-grouped cross-validation** to prevent speaker leakage
- **Platt scaling** for probability calibration
- Out-of-distribution detection and bias warnings for responsible screening

### ❄️ AgriTrack — *Cold Storage Management App (AWS, in production)*

A cloud application built and deployed for a family cold storage business, iterated across multiple release cycles based on real operational needs.

- **Serverless AWS architecture:** Lambda · DynamoDB · S3 / CloudFront
- Built for and used by an actual business — not a demo
- *(Add a line here on what it manages — inventory, storage bookings, tracking, etc.)*

### 🔹 NLP Transformer Benchmarking

- Fine-tuned DistilBERT (76% validation accuracy); benchmarked against SVM and Logistic Regression baselines
- Tokenization, attention masks, stratified splitting, and hyperparameter tuning across text classification, summarization, Q&A, and translation

### 🔹 YOLOv5 Custom Object Detection

- Custom dataset prep in YOLO format with modified class definitions
- Fine-tuned Ultralytics YOLOv5 weights; evaluated with precision, recall, and mAP

---

## 💼 Experience

### 🤖 AI Developer Intern — Semper8 International
**Sept 2023 – Dec 2023 | Toronto, ON**

Prototyped an AI-driven candidate assessment system combining speech emotion recognition and NLP.

- CNN-based speech emotion recognition (RAVDESS, TESS, CREMA-D, SAVEE; ~62% baseline) using MFCC/spectrogram features
- Hybrid multimodal architecture fusing audio (CNN) and text (LSTM over ASR transcripts); evaluated early vs. late fusion
- Built a GUI prototype with a retraining pipeline (preprocessing, stratified splits, model versioning)

### 🔬 Research Assistant — University of South Florida
**May 2021 – Aug 2021 | Tampa, FL**

Applied AI research in human–robot interaction.

- Interactive workflows for the Pepper robot using computer vision + face/engagement tracking
- Integrated Dialogflow with the Misty robot and Google Speech-to-Text/Text-to-Speech for a full audio → text → intent → response → speech pipeline

---

## 🛠 Tech Stack

**Languages:** Python, JavaScript
**ML/DL:** PyTorch, TensorFlow, Scikit-learn
**NLP / LLM:** HuggingFace Transformers, PubMedBERT, RAG (hybrid retrieval, rerankers), Groq, NLTK, SpaCy
**Vision:** YOLOv5, OpenCV
**Audio:** Librosa, Praat, MFCC
**Data & Cloud:** AWS (Lambda, DynamoDB, S3, CloudFront, EC2), serverless architecture
**Serving & Tools:** FastAPI, Hugging Face Spaces, Git, Jupyter

---

## 📍 Education

🎓 **Postgraduate Certificate, Data Science** — George Brown College, Toronto
📅 Jan 2023 – Dec 2023 · GPA 3.74/4.0

🎓 **Postgraduate Certificate, Cloud Computing** — Humber College, Etobicoke
📅 Jan 2022 – Aug 2022 · GPA 4.0/4.0

🎓 **B.Sc. Computer Science** — University of South Florida, Tampa
📅 Jan 2019 – Dec 2021 · GPA 3.19/4.0

---

## 📫 Let's Connect

📧 <vpatel2398@gmail.com>
🔗 [LinkedIn](https://www.linkedin.com/in/vivek-patel-7634a1130/)

If a project here was useful, a ⭐ is always appreciated!
