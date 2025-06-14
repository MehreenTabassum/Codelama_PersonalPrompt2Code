# AI-Powered Code Generator with History
A local, LLM-powered code generation app**(Codelama-PersonalPrompt2Code),** that takes language prompts and generates code using **CodeLlama** from **Ollama**, built with **LangChain** and a **Gradio UI**. It also keeps propmt-response history for comparison and better usability. 

**🚀 Features**

- 🧠 Uses CodeLLaMA locally (via Ollama) — no API key needed

- 📜 Generates code from natural language prompts

- 🐍 Supports Python and JavaScript

- 🕒 Keeps session history of prompts and responses

- 🧩 Built with LangChain + Gradio

**🛠️ Tech Stack**
- Ollama – to run LLaMA models locally

- CodeLLaMA – fine-tuned for code generation

- LangChain – LLM orchestration

- Gradio – UI for interacting with the model

- Python (3.10+)

**📦 Installation**
**1. Clone the repo**
```bash```
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name 

**2. Set up a virtual environment**
```bash```
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

**3. Install dependencies**
```bash```
pip install -r requirements.txt

**4. Install and run CodeLlama Using Ollama**
```bash```
ollama run codellama


