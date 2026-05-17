✉ Email: [ntq2005nu@gmail.com](mailto:ntq2005nu@gmail.com)  
🌐 GitHub: [ntq05](https://github.com/ntq05)  
🔗 LinkedIn: [Nguyen Thien Quan](https://linkedin.com/in/ntq05)

---

## About Me
I am a Data Science undergraduate at Ho Chi Minh City International University with practical experience in machine learning, computer vision, NLP, and AI pipelines. I enjoy building end-to-end solutions, optimizing operational outcomes, and exploring applied AI projects that create measurable impact.

---

## Core Skills

**Technical Skills:**

- Programming: Python (pandas, NumPy), SQL
- ML & DL: scikit-learn, PyTorch; classical ML (Logistic Regression, LightGBM, XGBoost, CatBoost); model training and evaluation on imbalanced data
- CV & NLP: image classification and basic segmentation; CNNs (MobileNetV3), Vision Transformers (DINOv2); text processing; embeddings and RAG (Sentence Transformers, FAISS)
- Data: data preprocessing, feature engineering, exploratory data analysis, data visualization (Matplotlib, Seaborn)
- Deployment & Tools: FastAPI (REST APIs, asynchronous inference), Streamlit (rapid prototyping), Git/GitHub, Joblib, basic Spark
- Methodology: time-aware validation, cross-validation, threshold optimization, cost-sensitive and risk-aware ML, experiment tracking under data and compute constraints

**Additional Skills:**
- Problem solving, analytical and critical thinking
- Teamwork, presentation, communication

---

## Education

**Ho Chi Minh City International University (HCMIU)**  
*Bachelor of Science in Data Science* | GPA: 3.45/4.0  
*Expected Graduation:* 09/2027 | Ho Chi Minh, Vietnam

---

## Research & Experience

**Undergraduate Research Member – IT Lab**  
05/2025 - Present | HCMIU
- Participated in research discussions and paper analysis on deep learning and generative models (ResNet, U-Net, DDPM, Improved DDPM)
- Summarized and presented key ideas from research papers to guide lab experiments
- Contributed to brainstorming model ideas and experimental directions for lab projects

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
