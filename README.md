# Hi, I'm Sanskar Modi 👋

AI Engineer focused on building production-grade ML systems — from agentic pipelines to deployable APIs.

📍 Bennett University, India · Graduating May 2027  
📧 sanskarmodi.dev@gmail.com  
🌐 [Portfolio](https://sanskarmodi8.github.io) · [LinkedIn](https://www.linkedin.com/in/sanskar-modi-ba53a2267) · [Kaggle](https://www.kaggle.com/sanskarmodi8)

---

## Production Projects

### Leave Policy AI Agent — Live Production Agent
**Google ADK + ReAct · Google Cloud Run · FastAPI · Snowflake**

Two-path hybrid architecture: deterministic fast-path handles ~70% of queries at sub-100ms with zero LLM cost. Agentic path for complex multi-turn reasoning. PII detection/redaction, prompt sanitization, circuit breaker with automatic fallback, 80%+ test coverage across unit + integration + security attack tests.

**[→ Hit the live API](https://leave-policy-agent-641772618787.us-central1.run.app/docs)** · [Code](https://github.com/sanskarmodi8/leave-policy-agent)
```bash
curl -X POST https://leave-policy-agent-641772618787.us-central1.run.app/chat \
  -H "Content-Type: application/json" \
  -d '{"message": "What is my leave balance?", "session_id": "demo", "employee_id": "E001"}'
```

---

### AtlasRAG — Hybrid RAG with Knowledge Graph
**FastAPI · Qdrant · LangChain · Next.js · Hugging Face Spaces · Vercel**

Hybrid retrieval: dense embeddings + BM25 + concept co-occurrence graph expansion. Recall@5 = 1.00 on multi-section academic document QA. Citation-aware generation, query rewriting, conversation memory.

**[→ Live App](https://atlas-rag.vercel.app)** · [Code](https://github.com/sanskarmodi8/Atlas-RAG)

---

### Brain Tumor Segmentation — Medical CV
**PyTorch · MONAI · Swin UNETR · DVC · Streamlit**

Multi-modal MRI segmentation on 40GB BraTS 2024 GLI dataset. 99.94% accuracy (avg loss 0.0121). Reproducible DVC pipeline with train/val/test splits. 3D axial/coronal/sagittal visualization.

**[→ Live App](https://sanskarmodi8-brain-tumor-segmentation-app-v4gu5u.streamlit.app)** · [Code](https://github.com/sanskarmodi8/brain_tumor_segmentation)

---

### MarketMind — RL Trading System
**PPO · PyTorch · MLflow · DVC · Streamlit · Yahoo Finance**

Bitcoin trading agent achieving **203.8% total return vs 124.1% buy-and-hold baseline**. Custom reward shaping with transaction costs and turnover penalty. Automated weekly retraining via single-command DVC pipeline.

**[→ Live App](https://marketmind-sanskarmodi.streamlit.app)** · [Code](https://github.com/sanskarmodi8/MarketMind)

---

### DeepDetect — Deepfake Detection
**PyTorch · MediaPipe · OpenCV · FastAPI · Gradio · Hugging Face**

Video deepfake detection on FaceForensics++ dataset (1,000 videos/subcategory). 93% accuracy / F1. Visual explainability via heatmaps. Gradio UI on Hugging Face Spaces, FastAPI backend for production use.

**[→ Live Demo](https://huggingface.co/spaces/SanskarModi/deepdetect)** · [Code](https://github.com/sanskarmodi8/DeepDetect)

---

## Open Source

**[sktime](https://github.com/sktime/sktime)** — Python's leading time series ML library · 50,000+ users · 3,000+ GitHub stars

Merged 2 production-ready forecasting algorithms into main branch ([PR #7909](https://github.com/sktime/sktime/pull/7909)):
- Bias-adjusted Box-Cox forecaster
- DA-RNN (Dual-stage Attention RNN) forecaster

Full code review, CI pipeline, and type-hint compliance.

---

## Active Work

- **MetaGPT-XL** — Production-grade multi-agent system (team of 5, in progress)
- **Whitebox Hallucination Reduction in LLMs** — Hyperparameter-driven research study (team of 3, in progress)

---

## 🛠 Tech Stack

| Area | Tools |
|------|-------|
| LLM & Agents | Google ADK, LangChain, LiteLLM, ReAct Pattern |
| ML / DL | PyTorch, Scikit-learn, MONAI |
| Production | FastAPI, Docker, Google Cloud Run, Azure Portal |
| MLOps | MLflow, DVC |
| UI | Streamlit, Gradio |
| Languages | Python, Java 

---
## 📊 GitHub Stats
![Stats](https://github-readme-stats.vercel.app/api?username=sanskarmodi8&show_icons=true&theme=dark&hide_border=true&count_private=true)
