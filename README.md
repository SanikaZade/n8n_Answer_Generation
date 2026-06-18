# CBSE Physics Answer PDF Generator using n8n 

## Overview

This project automates the generation of CBSE Class 12 Physics answers from NCERT chapter PDFs using n8n and Google Gemini AI.

The workflow extracts chapter content from a PDF, identifies exercise questions, automatically classifies them by difficulty level, generates structured CBSE-style answers, and exports the final results as a formatted PDF answer sheet.

---

## Features

* PDF Chapter Upload
* Automatic Text Extraction
* Exercise Question Detection
* Question Classification

  * SAQ LOW
  * SAQ MID
  * SAQ HARD
  * NUMERICAL
  * DERIVATION
* AI-Powered Answer Generation
* Formula & Source References
* Step-by-Step Numerical Solutions
* PDF Answer Sheet Generation
* Fully Automated n8n Workflow

---

## Workflow

PDF Upload
    ↓
Extract Text
    ↓
Question Extraction
    ↓
Split Questions
    ↓
Answer Generation
    ↓
Merge Answers
    ↓
Generate PDF
    ↓
Output PDF

---

## Tech Stack

* n8n
* Google Gemini API
* JavaScript
* PDF Processing
* Workflow Automation

---

## Project Structure

cbse-physics-answer-pdf-generator/

├── workflows/
│   └── cbse_answer_generation.json
│
├── screenshots/
│   └── workflow.png
│
├── sample-files/
│   └── chapter8.pdf
│
├── sample-output/
│   └── answer_sheet.pdf
│
└── README.md

---

## Workflow Screenshot


<img width="1492" height="536" alt="Screenshot 2026-06-18 113251" src="https://github.com/user-attachments/assets/79b79ff9-7538-4b03-a0ed-1e4d78cd5d19" />


---

## How to Use

### 1. Import Workflow

Import the workflow JSON file into n8n.

### 2. Configure Gemini API

Add your Google Gemini API credentials.

### 3. Upload Chapter PDF

Provide the NCERT Physics chapter PDF.

### 4. Execute Workflow

Run the workflow.

### 5. Download Output

The workflow generates a structured PDF answer sheet containing answers for all exercise questions.

---

## Example Output

The generated PDF contains:

* Question Number
* Question Text
* Difficulty Classification
* Answer
* Formula Reference
* Source Reference
* Numerical Steps (if applicable)
* Derivation Steps (if applicable)

---

## Future Improvements

* Multi-Chapter Support
* Multi-Subject Support
* Answer Validation
* Marking Scheme Integration
* Automatic PDF Formatting Enhancements


## License

This project is intended for educational and learning purposes.
