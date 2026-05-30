✉ Email: [ntq2005nu@gmail.com](mailto:ntq2005nu@gmail.com)  
🌐 GitHub: [ntq05](https://github.com/ntq05)  
🔗 LinkedIn: [Nguyen Thien Quan](https://linkedin.com/in/ntq05)

---

## About Me

Data Science undergraduate at Ho Chi Minh City International University with hands-on experience in machine learning, computer vision, NLP, retrieval systems, and LLM applications. I have built end-to-end AI solutions spanning multimodal AI, RAG pipelines, agentic workflows, and model deployment. My interests lie in developing production-ready AI systems and conducting applied research in multimodal understanding, retrieval, and generative AI.

---

## Core Skills

### Technical Skills

- **Languages:** Python, SQL

- **Machine Learning:** scikit-learn, XGBoost, LightGBM, CatBoost, Ensemble Learning, Imbalanced Learning

- **Deep Learning:** PyTorch, CNNs, Vision Transformers (DINOv2), Transfer Learning, PEFT/LoRA

- **Generative AI & LLMs:** LangChain, LangGraph, RAG, Multi-Agent Systems, Hugging Face Transformers, Sentence Transformers, FAISS, Prompt Engineering, Tool Calling

- **Computer Vision:** Image Classification, Semantic Segmentation, Medical Imaging, Feature Extraction

- **Deployment & Infrastructure:** FastAPI, Docker, Docker Compose, PostgreSQL, Streamlit, Git/GitHub

- **Data Science:** EDA, Feature Engineering, Statistical Modeling, Model Evaluation

- **Research Interests:** Multimodal Retrieval, Video Understanding, Vision-Language Models, Agentic AI Systems

### Additional Skills:
- Problem solving, analytical and critical thinking
- Teamwork, presentation, communication

---

## Education

**Ho Chi Minh City International University (HCMIU)**  
*Bachelor of Science in Data Science* | GPA: 3.45/4.0  
*Expected Graduation:* 09/2027 | Ho Chi Minh, Vietnam

---

## Experience

**AI Engineer Intern | Hiptech Solution**

*02/2026 – 05/2026*

- Designed and improved an LLM pipeline with modules for routing, retrieval, validation, and summarization, improving reliability and reducing hallucinations.
- Developed an LLM-based intent routing system, improving classification accuracy and pipeline stability.
- Built and optimized RAG-based retrieval modules with semantic search fallback, improving document matching and response relevance.
- Improved multi-turn interactions and multi-agent chatbot performance by handling edge cases, implementing validation logic, and refining retrieval workflows, reducing errors and improving response consistency.

---

## Selected Projects

### Agentic Corporate Simulation: Multi-Agent Cognitive System
*04/2026 – Present*

[🌐 View Project Repository](https://ntq05.github.io/AI-Co-worker-Multi-Agent-System/)

- Designed and implemented a **multi-agent corporate simulation system** using a Supervisor–Worker architecture (CEO, CHRO, Manager), enabling structured and role-based decision-making workflows
- Built a **LangGraph-based state machine** with summarization, routing, and execution nodes, ensuring consistent reasoning flow and reducing context fragmentation across multi-turn interactions
- Developed an **intelligent memory mechanism** combining short-term state tracking and progressive summarization, reducing token usage while preserving long-term conversational context
- Implemented **stateful persistence with PostgreSQL (AsyncPostgresSaver)**, enabling seamless conversation recovery across sessions
- Integrated **LangChain Tool Calling for dynamic agent routing**, improving response relevance via intent-aware agent selection
- Containerized the entire system using **Docker & Docker Compose**, orchestrating FastAPI, PostgreSQL, and vector storage services, enabling reproducible deployment and simplified environment setup
- Deployed a **production-ready FastAPI backend**, supporting asynchronous request handling and scalable API integration
- Designed an extensible **cognitive architecture roadmap** (semantic, episodic, procedural memory), laying the foundation for advanced reasoning and knowledge systems

### Cheating Detection with Cost-Sensitive ML (Kaggle Competition)
*07/12/2025 – 25/12/2025*

[🌐 View Project Website](https://ntq05.github.io/kaggle-mercor-cheating-detection/)

- Built predictive models to detect cheating in online interviews using anonymized behavioral and network features
- Engineered graph-based relational features and derived ratios/differences to capture network effects
- Handled missing data using indicators and iterative imputation with tree-based regressors
- Trained an ensemble of LightGBM, XGBoost, and CatBoost with stratified K-Fold cross-validation and stacking
- **Optimized decision thresholds to minimize operational cost across auto-pass, manual review, and auto-block decisions**

### Fine-Tuned Medical AI Assistant (Llama-3.1-8B)
*24/05/2026-30/05/2026*

[🌐 View Project Website](https://ntq05.github.io/Llama-3.1-Medical-Consultant/)

- Developed an end-to-end domain-adaptation pipeline to fine-tune Llama-3.1-8B-Instruct into a specialized, empathetic AI Medical Assistant using patient-doctor dialogues, ensuring strict adherence to clinical safety disclaimers.
- Implemented low-resource parameter-efficient fine-tuning (PEFT/LoRA) integrated with BitsAndBytes 4-bit (NF4) quantization via Unsloth, drastically reducing the VRAM footprint and enabling rapid convergence within 1 epoch on a single T4 GPU.
- Designed a structured, production-grade data preprocessing workflow that globally injected custom system personas and multi-turn clinical chat templates while eliminating token anomalies and text noise
- Built a rigorous dual-layered automated benchmarking suite to evaluate text generation quality against the base model, measuring both lexical alignment (achieving +618% BLEU and +210% ROUGE-2 improvements) and semantic accuracy (+3.0% BERTScore F1).

### Rice Disease AI System

#### Youth Digital Citizen Challenge 2025 – AI for Climate (Twin Transition)
*11/2025-01/2026*

[🌐 AI Training Repository](https://ntq05.github.io/rice-AI-models-training-demo/)

[🌐 AI API Services](https://ntq05.github.io/rice-ai-service-demo/)

Role: AI Engineer – Model Development & Backend API

Description: Designed and deployed an AI-powered backend system for rice disease detection and outbreak forecasting, supporting early warning and decision-making for climate-resilient agriculture.

Key Contributions:

- Built a multi-stage AI pipeline:

  - Rice / non-rice image filtering (MobileNetV3)

  - Rice disease classification using DINOv2 (ViT) as a frozen feature extractor

  - 7-day outbreak risk forecasting using XGBoost on temporal & climate signals

- Developed a FastAPI-based ML service with:

  - Asynchronous inference using background tasks

  - REST APIs for image-based diagnosis and outbreak prediction

  - RAG-based disease knowledge retrieval (FAISS + Sentence Transformers)

- Designed time-aware data splitting and threshold tuning to handle highly imbalanced outbreak data (~9%)

- Packaged trained models as reusable artifacts for rapid deployment and demo

Tech Stack: PyTorch, DINOv2, XGBoost, FastAPI, FAISS, Sentence Transformers, scikit-learn

### Brain Tumor Classification & Segmentation

#### AI Hackathon Finalist

*09/2025 - 12/2025*

[🌐 View Project Repository](https://github.com/ntq05/BrainTumorAI_Demo)

- Developed an end-to-end computer vision pipeline for brain tumor classification and segmentation from MRI images using ResNet18 and ResUNet, enabling automated tumor detection and region extraction

- Built preprocessing and augmentation workflows for medical imaging datasets, including resizing, rotations, flips, and mask normalization, improving robustness across varying image conditions

- Implemented classification and segmentation training pipelines with validation-based checkpointing, early stopping, and learning rate scheduling to improve training stability and model reliability

- Applied MC Dropout for uncertainty estimation during inference, improving prediction confidence assessment for medical imaging outputs

- Deployed an interactive Streamlit application for real-time tumor classification and segmentation visualization, supporting end-to-end inference and demo workflows

Tech Stack: PyTorch, torchvision, segmentation_models_pytorch, scikit-learn, Streamlit, NumPy, Pandas, Git/GitHub

---

## Awards & Achievements
- Academic Excellence Scholarship – Highest GPA in Data Science Department (Semester 2, 2023)

---

## Currently Learning
- NLP & Retrieval-Augmented Generation (RAG)
- Advanced ML pipelines and deployment
