# LegalEaseAI — AI-Powered Legal Document Generator

## 📖 Project Overview

LegalEaseAI is an AI-powered legal document generation application designed to help users create basic legal documents through a simple and user-friendly interface.

The application combines Generative AI, FastAPI, and Streamlit to provide a structured workflow for generating legal documents based on user-provided information.

Users can select a document type, enter party details and additional information, and generate a formatted legal document that can be downloaded in DOCX format.

The project demonstrates the practical use of Artificial Intelligence, backend API development, frontend application development, and automated document generation.

## 👥 Team Members

| Name | Role | Responsibility |
| ---- | ---- | -------------- |
| **S. Devibala** | **Team Leader** | Project coordination, integration, team management and overall project supervision |
| **N. Ashwini** | AI/ML Developer | AI integration, Gemini integration and AI-powered legal document generation |
| **M. Thirumalai** | Backend Developer | FastAPI backend, API routes, schemas and application logic |
| **Velmurugan** | Frontend Developer | Streamlit interface, user interaction and document generation interface |
| **Yogesh** | Testing & Documentation Developer | Application testing, output validation and project documentation |

## ✨ Features

* AI-powered legal document generation
* Rental Agreement generation
* NDA (Non-Disclosure Agreement) generation
* User-friendly document generation interface
* Party details input
* Additional legal details input
* DOCX document generation
* Download generated legal documents
* Gemini AI integration
* FastAPI-based backend
* Streamlit-based frontend
* API documentation using FastAPI Swagger UI
* Structured document formatting
* Simple and easy-to-use workflow

## 🛠️ Technologies Used

| Technology | Purpose |
| ---------- | ------- |
| Python | Core programming language |
| FastAPI | Backend API development |
| Uvicorn | ASGI server |
| Streamlit | Frontend user interface |
| Python-DOCX | DOCX document generation |
| Gemini API | AI-powered legal document generation |
| HTML | Web structure |
| JSON | Data exchange and API communication |
| Git | Version control |
| GitHub | Project repository and collaboration |

## 📁 Project Structure

```text
LegalEaseAI/
│
├── api/
│   ├── index.py
│   └── requirements.txt
│
├── backend/
│   ├── ai_core/
│   │   └── gemini_generator.py
│   │
│   ├── document__generators/
│   │   ├── __init__.py
│   │   └── formatters.py
│   │
│   ├── __init__.py
│   ├── config.py
│   ├── main.py
│   ├── routes.py
│   └── schemas.py
│
├── frontend/
│   └── app.py
│
├── index.html
├── pyproject.toml
├── requirements.txt
├── .gitignore
└── README.md
Installation
1. Clone the Repository
git clone https://github.com/25bsccsds40-maker/LegalEaseAI.git
2. Open the Project Folder
cd LegalEaseAI
3. Create a Virtual Environment
python -m venv venv
4. Activate the Virtual Environment

For Windows:

venv\Scripts\activate

For macOS/Linux:

source venv/bin/activate
5. Install Required Dependencies
python -m pip install -r requirements.txt

If required, install the main packages separately:

python -m pip install fastapi uvicorn streamlit python-docx
▶️ Running the Project
Start the Backend

Open a terminal in the project root folder and run:

python -m uvicorn backend.main:app --reload

The FastAPI backend will run at:

http://127.0.0.1:8000
API Documentation

FastAPI provides interactive API documentation at:

http://127.0.0.1:8000/docs

The Swagger UI allows users and developers to view and test the available API endpoints.

Start the Frontend

Open a second terminal and run:

python -m streamlit run frontend/app.py

The Streamlit application will be available at:

http://localhost:8501
📄 Supported Legal Documents
🏠 Rental Agreement

LegalEaseAI provides an interface for entering party details and rental-related information to generate a basic rental agreement document.

🤝 Non-Disclosure Agreement (NDA)

The application also provides an NDA option for generating a basic non-disclosure agreement document based on the information provided by the user.

🔄 Application Workflow
User
  │
  ▼
Streamlit Frontend
  │
  ▼
Select Legal Document Type
  │
  ▼
Enter Party Details
  │
  ▼
Enter Additional Details
  │
  ▼
AI / Document Generation
  │
  ▼
Formatted Legal Document
  │
  ▼
Download DOCX
🤖 AI Integration

LegalEaseAI is designed with an AI-powered architecture for generating legal document content.

The project includes an AI core responsible for handling AI-based document generation and provides a foundation for integrating Google's Gemini API into the legal document generation workflow.

🔮 Future Enhancements
Advanced AI-powered legal document generation
More legal document templates
Full Gemini API integration
PDF export
Legal document preview
User authentication and accounts
Database integration
Document history
Multi-language legal document generation
Legal clause recommendations
Improved document formatting
Cloud deployment
Secure document storage
More advanced AI assistance
Mobile-responsive interface
⚠️ Disclaimer

LegalEaseAI is an educational and academic project.

The generated documents are intended for general informational and educational purposes only and should not be considered a substitute for professional legal advice.

Users should consult a qualified legal professional for legal matters requiring professional legal advice.

📌 Project Status

Status: Active Development

LegalEaseAI is an academic project focused on developing an AI-powered legal document generation workflow using Generative AI, FastAPI, Streamlit, and automated document generation.

📜 License

This project is developed for educational and academic purposes.

👩‍💻 Developed By

LegalEaseAI Team

B.Sc. Computer Science with Data Science

Academic Project

Thiruthangal Nadar College
