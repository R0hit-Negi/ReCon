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

### Step 2: Run index.html code in any folder

### Step 3: Use Tab-1 to add prompts
Sample prompts are given for Clause A.5.11 & A.8.11

Additonaly, ground truth for Clause A.5.11 is "Conformity" and for Clause A.8.11 is "Non-Conformity"

### Step 3: Use Tab-2 to select the models and configure them
Keep your temperature "0"

### Step 4: Run Evaluation

### Step 5: See the results




### Do Not Referesh Page 