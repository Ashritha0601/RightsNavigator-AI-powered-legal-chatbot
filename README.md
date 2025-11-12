# ⚖️ Legal_aid_Chatbot / RightsNavigator

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-0.99-orange?logo=streamlit&logoColor=white)
![GitHub Repo](https://img.shields.io/badge/Repo-GitHub-black?logo=github)


**Created for GradInnoHack 2025 at the University of North Texas**  

🎉 **Thrilled to announce our hackathon project:**  
🔷 **RightsNavigator: AI-Powered Legal Guidance for the Disabled**  

This project goes beyond a prototype — it’s a mission to make legal rights truly accessible for people with disabilities.

---

## 💡 The Problem
Legal documents are often too complex and scattered, making it difficult for people with disabilities to access support when they need it most.  
❗ This gap can lead to missed accommodations, unclaimed benefits, and lack of independence.

---

## 🛠️ Our Solution
**RightsNavigator** is an AI-powered legal assistant that:  
✅ Breaks down disability rights laws into simple, everyday language  
✅ Provides instant, personalized answers to legal queries  
✅ Offers a voice interface for accessibility  
✅ Uses RAG (Retrieval-Augmented Generation) with **Llama 3.2 + ChromaDB**

---

## 🎯 Key Features
- Conversational interface for legal queries  
- Retrieval of legal information from documents and databases  
- Intelligent query handling (`query_engine.py`)  
- Web UI for user interaction (`webui.py`)  
- Notebook (`gnu.ipynb`) for testing and prototyping  
- Easy extension of legal topics and document sources  

---

## 💻 Tech Stack
- **Backend:** Python  
- **Frontend:** Streamlit  
- **AI Models:** HuggingFace Transformers, LlamaIndex, OLLAMA (Llama 3.2)  
- **Database:** ChromaDB for vector-based retrieval  

---

## 📊 Impact at a Glance
✔️ Legal support in education, healthcare, and employment  
✔️ Step-by-step guidance for accommodations  
✔️ Voice-friendly experience for users with mobility impairments  


---

## 📂 Project Structure
- **Data_Folder/ – Contains legal documents and knowledge base
- **chroma_db/ – Database index for efficient retrieval
- **persisted_index/ – Stored indices for reuse
- **query_engine.py – Core query processing module
- **webui.py – Web interface for chat interaction
- **gnu.ipynb – Notebook for testing and prototyping
- **requirements.txt – Python dependencies
- **.gitignore.txt – Git ignore configuration

---

## 👩‍💻 Team & Mentors
- **Team Members:** Ashritha Battula, Harshitha Devabhaktuni, Arun G, Pavan Kalyan Natukula, Chinmai Kaveti
- **Mentors:** Haihua Chen & Brady Lund  
- **Industry Inspiration:** Babak Alipour, Ray Morsali, PhD, MBA, Dr. Tanha  
- **Organizers:** Hadiseh Gooran & Farhan Ar Rafi  

---

## 🚀 Getting Started
```bash
git clone https://github.com/Ashritha0601/RightsNavigator-AI-powered-legal-chatbot.git
cd Legal_aid_Chatbot
pip install -r requirements.txt
python webui.py
```

Then open your browser and navigate to the local web UI to start interacting with RightsNavigator.
##🔮 Next Steps
Add multilingual support
Expand to new legal domains
Collaborate with NGOs to reach more people in need
💙 Tech with purpose. AI with empathy.
Let’s keep building tools that empower and include.
