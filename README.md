<div align="center">

# GenAI Clinical Notes

### AI-Powered Automated Clinical Documentation System

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com)
[![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logoColor=white)](https://langchain.com)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![Healthcare](https://img.shields.io/badge/Healthcare%20AI-FF4081?style=for-the-badge&logoColor=white)](https://github.com/Avvv19)

</div>

---

## Overview

**GenAI Clinical Notes** is an AI-powered clinical documentation system that automatically generates structured medical notes from physician-patient conversations. Leveraging large language models (LLMs) and medical NLP, it dramatically reduces documentation burden on healthcare providers — saving hours per day and improving note accuracy.

---

## Key Features

- **Automated SOAP Notes** — Generate Subjective, Objective, Assessment, Plan notes from transcripts
- **Discharge Summaries** — AI-structured discharge documentation compliant with hospital standards
- **Referral Letters** — Professional referral letters generated in seconds
- **ICD-10 Code Suggestions** — Automatic diagnosis code recommendations
- **Voice-to-Note Pipeline** — Speech transcription to structured clinical note
- **Template Customization** — Adapt templates per specialty (cardiology, oncology, primary care)
- **FHIR-Compatible Output** — Export notes in FHIR R4 format for EHR integration

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

---

## Workflow

```
Audio/Text Input
    |
    v
Transcription (Whisper/Azure Speech)
    |
    v
Medical NLP Processing (LangChain + LLM)
    |
    v
Structured Clinical Note Generation
    |
    |-- SOAP Notes
    |-- Discharge Summaries
    |-- Referral Letters
    |-- ICD-10 Codes
    v
FHIR Export / EHR Integration
```

---

## Getting Started

```bash
# Clone the repository
git clone https://github.com/Avvv19/genai-clinical-notes.git
cd genai-clinical-notes

# Install dependencies
pip install -r requirements.txt

# Set environment variables
export OPENAI_API_KEY=your_api_key

# Run the application
python app.py
```

---

## Use Cases

- **Primary Care Physicians** — Automate routine visit documentation
- **Specialists** — Generate specialty-specific note templates
- **Hospitalists** — Rapid admission and discharge summaries
- **Telehealth Platforms** — Real-time note generation during video consultations

---

## Compliance & Privacy

- HIPAA-compliant data handling design
- No PHI stored in external services
- On-premise deployment option available
- Audit trail for all generated documents

---

## Author

**Venkata Vivek Varma Alluru** | AI in Healthcare

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/venkatavivekvarmaalluru/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Avvv19)
