# MCQ Generator using LangChain + OpenAI

## Project Overview
This project is a **Multiple-Choice Question (MCQ) Generator** that uses **OpenAI’s GPT models** (via LangChain) to automatically generate quizzes from input text or documents such as PDFs.  
It can extract text, generate questions, provide answer choices, and identify the correct answer.

---

## Features
- Generate **MCQs** from any text or PDF file  
- Use **LangChain** chains for modular and structured prompt execution  
- **Cost tracking** with OpenAI API usage monitoring  
- Save results in **JSON** or **Pandas DataFrames** for further analysis  
- Configurable **prompt templates** for flexible question generation  

---
## Usage

- Upload or provide text input (e.g., from a PDF)

- The system will:

- Extract text

- Generate MCQs using GPT models

- Store MCQs in JSON or display in a DataFrame

## Future Improvements
- Support for RAG (Retrieval-Augmented Generation) with knowledge bases
- Export quizes directly to google forms

