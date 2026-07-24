# ReCon
# ReCon: LLM Ground Truth Evaluation Engine

ReCon is a simple, self-contained HTML, CSS, and native JavaScript application designed to benchmark local backend Large Language Models (LLMs) (such as Ollama) against annotated ground truth data. 

It features automated multi-tab evaluation workflows, live model discovery, duplicate prompt monitoring via content hashing, sequential/parallel execution modes, and an extensive statistical analysis suite (Confusion Matrix, Accuracy, Precision, Recall, F1 Score, MCC, Cohen's Kappa, and trend lines).

---

## 🚀 How to Use the Application

### Step 1: Start Your Local LLM Backend (Ubuntu)
Before launching the tool, verify that your models are installed and running on your Ubuntu platform, and make sure **CORS** is enabled so your browser can communicate with your local server.

1. Open your terminal and start Ollama with CORS enabled:
   ```bash
   OLLAMA_ORIGINS="*" ollama serve

### Do Not Referesh Page 