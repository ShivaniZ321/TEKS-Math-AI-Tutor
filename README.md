# TEKS-Math-AI-Tutor

# 🧩 Software Project Scope

## 📌 1. Project Overview
This project implements an end-to-end AI-powered chatbot built using modern Machine Learning, Generative AI, Prompt Engineering, and RAG architecture. The solution includes a Streamlit UI, an API backend (Python FastAPI), and integrations with HuggingFace embedding models—all running on Windows OS with containerized deployment options.

---

## 🎯 2. Objectives
- Develop a functional AI/ML-powered chatbot that accepts user's concept name as mathematical questions.
- UI also shows sample questions user can ask. 
- Integrate embeddings, vector search, and LLM inference pipelines.  
- Build a clean UI using Streamlit.  
- Implement a backend API using Python.  
- Containerize using Docker.  
- Maintain high-quality documentation and testing standards (optional).

---

## 🛠️ 3. Features & Requirements

### **Core Features**
- Streamlit-based user interface  accepts user input 
- Backend API (FastAPI or ASP.NET Core)  
- Vector database (FAISS / ChromaDB)  
- HuggingFace embeddings 
- LLM inference (OpenAI/Llama/Mistral/Other)  
- Logging and monitoring support (optional)

### **Non-Functional Requirements**
- Modular and scalable architecture  
- Container-ready (Docker/Podman)  
- Average response time < 10 seconds   ( will be decided based on model pricing and token input later)
- Secure API key management using `.env`  
- Reliable error handling and retry logic  

---

## 📁 4. Project Deliverables

| Deliverable | Description |
|------------|-------------|
| Source Code | Complete implementation of UI, backend, and ML components |
| README | Setup instructions, architecture, usage guide |
| Architecture Diagram | Visual system overview |
| ML Notebooks | Embeddings & evaluation notebooks |
| Dockerfile | Container build configuration |
| Test Cases | Unit and integration tests | (Optional)

---

## 🧱 5. System Architecture

### **High-Level Flow**
1. User interacts with Streamlit UI  
2. UI sends request to backend API  
3. API performs tokenization & embeddings  
4. Vector DB performs similarity search  
5. LLM generates response  
6. UI displays final result  

### **Architecture Diagram (Mermaid)**
TBD

---


### 📦 6. Tech Stack

| Category | Tools / Technologies |
|---------|----------------------|
| **Frontend** | Streamlit |
| **Backend** | FastAPI |
| **AI / ML Frameworks** | HuggingFace Transformers |
| **Embeddings Models** | all-MiniLM-L6-v2, InstructorXL, local HF models |
| **LLMs** | GPT-4o-mini|
| **Vector Databases** |  ChromaDB |
| **Containerization** | Docker Desktop |
| **OS / Environment** | Windows 10/11 (Dev environment) |
| **Package Mgmt** | pip |

---

### 🧪 7. Testing Strategy

#### ✔ Unit Tests
- Python: `pytest`
- .NET: MSTest / xUnit

#### ✔ Integration Tests
- API endpoint tests  
- UI-to-backend workflow tests  

#### ✔ Load Testing
- Locust or JMeter  

#### ✔ LLM Quality Testing
- Guardrail validation  
- Hallucination checks  
- Prompt consistency testing  

---

### 🚀 8. Deployment Plan

## **Local Setup (Windows OS)**
1. Clone repository  
2. Install dependencies  
3. Create and configure `.env` file  
4. Start backend API  
5. Start Streamlit UI  

---

### **Docker Deployment**

docker build -t ai-project .
docker run -p 8080:8080 ai-project

---

### 📚 9. Dependencies

This project uses a combination of Python, AI/ML libraries,  and containerization tools on Windows OS.  
Below is the complete list of dependencies required for seamless development and deployment.

---

#### 🐍 Python Dependencies

##### **Core Packages**
- **Python 3.10+**
- **pip** (Package Manager)
- **virtualenv / conda** (Optional for environment isolation)

#### **Backend**
- `fastapi`
- `uvicorn`
- `pydantic`
- `python-dotenv`

#### **Frontend**
- `streamlit`

#### **AI / ML**
- `transformers` (HuggingFace models)
- `sentence-transformers` (for embedding models)
-  `chromadb`

#### **Data & Utilities**
- `pandas`
- `numpy`
- `requests`

#### **Testing** (Optional)
- `pytest`
- `httpx`

---



#### 🧰 10. System Tools & Environment

### **Essential Tools**
- **Windows 10/11** (Primary development OS)
- **VS Code** with:
  - Python Extension    
  - Docker Extension  
  - Markdown Preview

#### **Version Control**
- **Git**


#### **Containerization**
- **Docker Desktop for Windows**  


---


# 📝 11. Future Enhancements

Future improvements planned for this project:

- Add **RAG evaluation using RAGAS**  
- Implement **role-based authentication**  
- Add **analytics dashboard** (Streamlit/Plotly)  
- Generate questions with images

---

# 📄 License
This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute the code.

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository  
2. Create a feature branch  
3. Submit a pull request  

---

# ⭐ Acknowledgments

- HuggingFace Transformers for open-source models  
- Streamlit for rapid UI development  
- OpenAI 
- Docker for containerization tools  

