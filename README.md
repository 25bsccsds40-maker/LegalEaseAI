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
