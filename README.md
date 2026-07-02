# TalentLens AI: Intelligent Candidate Discovery & Ranking Engine

### Track: The Data & AI Challenge (Track 2)
**Team Name:** AI Avengers  
**Team Leader:** Upendra  

---

## 📌 Project Overview
TalentLens AI is an end-to-end Candidate Discovery and Ranking Engine built to solve the limitations of keyword-based Applicant Tracking Systems (ATS). Instead of exact string matching, this solution leverages semantic vector space search combined with a multi-agent validation layer to contextually match candidate profiles against incoming Job Descriptions (JDs).

## 🚀 Key Features
- **Semantic JD Breakdown:** Uses transformer embeddings to capture the true structural requirements of a role rather than surface-level terminology.
- **Dense Vector Retrieval:** Implements cosine similarity vector matching over structured candidate profiles for fast, sub-second screening.
- **Explanatory Re-Ranking:** Generates automated reasoning profiles for each rank score, giving recruiters full explainability behind an applicant's placement.
- **Data Validation & Anti-Hallucination Guardrails:** Employs a deterministic validation engine to catch timeline contradictions or suspicious profile attributes.

## 🛠️ Technical Stack
- **Language:** Python 3.10+
- **Frameworks:** FastAPI, LangChain / LangGraph
- **Vector Indexing:** FAISS (Facebook AI Similarity Search) / NumPy Matrix Operations
- **Data Processing:** Pandas, OpenPyXL
- **Embeddings:** `sentence-transformers/all-MiniLM-L6-v2`

## 📦 Installation & Setup

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
   cd YOUR_REPOSITORY_NAME
