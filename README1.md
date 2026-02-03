# Post-Operative Care Chatbot

A secure, patient-specific post-operative care chatbot that provides personalized recovery guidance, symptom triage, and emergency escalation for patients after surgery.

The system uses **FastAPI**, **Retrieval-Augmented Generation (RAG)**, **LLMs**, and **Docker** to ensure responses are grounded strictly in each patient’s medical data while enforcing strong safety constraints.

> ⚠️ This project is a **clinical support and triage assistant**, not a diagnostic tool and not a replacement for professional medical care.

---

## Features

- 🔐 **Role-based authentication**
  - Separate access for patients and doctors
- 🧠 **Patient-specific AI responses**
  - RAG ensures the AI only uses the authenticated patient’s data
- 🚦 **Symptom triage system**
  - Level 1: Routine guidance  
  - Level 2: Caution — recommend clinician follow-up  
  - Level 3: Emergency — trigger alert
- 🚨 **Emergency escalation**
  - Alerts emergency contacts for critical symptoms
- 🏥 **Doctor administration**
  - Add and manage patient medical records
- 🧾 **Safety-first LLM prompting**
  - Prevents hallucinated medications
  - Restricts advice to verified patient context
- 🐳 **Dockerized deployment**
  - Consistent setup across environments

---

## Tech Stack

- **Backend:** FastAPI (Python)
- **AI:** LLM (OpenAI / Gemini compatible)
- **RAG:** Vector embeddings over patient data
- **Database:** Redis
- **Auth:** JWT
- **Frontend:** HTML, CSS, JavaScript
- **Containerization:** Docker & Docker Compose

---

