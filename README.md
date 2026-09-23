<h1 align="center">Vivek Sharma</h1>

<p align="center">
  AI/ML Engineer · RAG Systems · LLM Inference · Multimodal AI<br/>
  Mumbai, India
</p>

<p align="center">
  <a href="mailto:vivektusharma@gmail.com"><img src="https://img.shields.io/badge/vivektusharma@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://linkedin.com/in/vivek-sharma-64951b24b"><img src="https://img.shields.io/badge/LinkedIn-Vivek%20Sharma-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://vivek02sharma.github.io/"><img src="https://img.shields.io/badge/Portfolio-vivek02sharma.github.io-3b82f6?style=flat-square&logo=githubpages&logoColor=white" alt="Portfolio"/></a>
  <a href="https://github.com/Vivek02Sharma"><img src="https://img.shields.io/badge/GitHub-Vivek02Sharma-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/></a>
  <a href="https://www.kaggle.com/viveksharmar"><img src="https://img.shields.io/badge/Kaggle-viveksharmar-20BEFF?style=flat-square&logo=kaggle&logoColor=white" alt="Kaggle"/></a>
  <a href="https://x.com/sudo_vivek"><img src="https://img.shields.io/badge/X-@sudo__vivek-000000?style=flat-square&logo=x" alt="X"/></a>
</p>

## About

I work at the intersection of applied ML research and production engineering. My focus is on retrieval-augmented generation, LLM inference optimization, and multimodal systems that hold up under real traffic. I care about measurable outcomes: time-to-first-token, cost per request, and evaluation pipelines that catch regressions before deployment.

## Featured Projects

<table>
  <tr>
    <td width="50%">
      <b><a href="https://github.com/Vivek02Sharma/MedVec-Scratch">MedVec-Scratch</a></b><br/>
      Medical sentence embeddings built <i>from scratch</i> — a Siamese Transformer (4 layers, 256-dim) with a custom BPE tokenizer (30k vocab), trained on 233k clinical triplets via Triplet Margin Loss.<br/>
    </td>
    <td width="50%">
      <b><a href="https://github.com/Vivek02Sharma/sam3-triton">sam3-triton</a></b><br/>
      Accelerated SAM3 (Segment Anything Model 3) inference using NVIDIA Triton Inference Server and TensorRT for low-latency, high-throughput production deployment.<br/>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <b><a href="https://github.com/Vivek02Sharma/AskRAG">AskRAG</a></b><br/>
      Agentic RAG system for querying US Federal Registry documents — async pipelines, Groq LLM, MySQL backend, and tool-calling architecture for real-time retrieval.<br/>
    </td>
    <td width="50%">
      <b><a href="https://github.com/Vivek02Sharma/End-to-end-mlops-with-mlflow">MLOps Pipeline with MLflow</a></b><br/>
      End-to-end medical cost prediction pipeline — 4 regression models with automated best-model selection (R² 99.68%), MLflow tracking & registry, FastAPI serving, Streamlit frontend.<br/>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <b><a href="https://github.com/Vivek02Sharma/ArtCycle">ArtCycle</a></b><br/>
      Unsupervised image-to-image translation with CycleGAN — transforms photos into paintings and back, no paired training data required. Live on Streamlit.<br/>
    </td>
    <td width="50%">
      <b><a href="https://github.com/Vivek02Sharma/NeuroScan">NeuroScan</a></b><br/>
      CNN that classifies brain tumor types (Glioma, Meningioma, Pituitary, No Tumor) from MRI scans. Live demo on Hugging Face Spaces.<br/>
    </td>
  </tr>
</table>

## Production Engineering Highlights

| System | Problem | Approach | Outcome |
|---|---|---|---|
| **Multimodal try-on** (Zyrobe) | High latency & cost for fashion image generation | `Qwen-Image-Edit` + Lightning LoRA via `vLLM-Omni` on RunPod serverless | 6.3–17.6s latency at $0.011–$0.060/image, benchmarked over 1,000+ generations |
| **Voice RAG agent** (AnvexSpeak) | Slow time-to-first-token broke conversational flow | Redis semantic caching + chunk-based token streaming from `vLLM`, multi-tenant Qdrant filtering | Reduced TTFT for real-time voice; enforced data privacy via SHA-256 dedup |
| **Policy chatbot** (AVA) | Risk of PII leakage & out-of-scope answers | LangChain + Qdrant + SambaNova Llama-4 across 26+ policies, `NeMo Guardrails` | Validated on 150+ test cases via `DeepEval`; earned full-time conversion |

## Technical Stack

**Languages & Frameworks**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-334155?style=flat-square)

**LLM & Generative AI**
![vLLM](https://img.shields.io/badge/vLLM-6366F1?style=flat-square)
![LiteLLM](https://img.shields.io/badge/LiteLLM-0EA5E9?style=flat-square)
![DeepEval](https://img.shields.io/badge/DeepEval-22C55E?style=flat-square)
![NeMo Guardrails](https://img.shields.io/badge/NeMo%20Guardrails-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Amazon Bedrock](https://img.shields.io/badge/Amazon%20Bedrock-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**MLOps & Cloud**
![Amazon SageMaker](https://img.shields.io/badge/Amazon%20SageMaker-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![RunPod](https://img.shields.io/badge/RunPod-7928CA?style=flat-square)
![Triton](https://img.shields.io/badge/Triton-76B900?style=flat-square&logo=nvidia&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)

**Data & Tools**
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC2438?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-334155?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
