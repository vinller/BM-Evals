# 🧠 BM Evaluation Tool

A web-based application to streamline Building Manager evaluations with features for generating evaluation documents, looking up records, logging results, and managing a question bank.

---

## ✨ Features

- 📄 Generate customizable .docx evaluation sets (student and evaluator copies)
- 🗂️ Organize questions by section (10 sections total)
- 🧠 Each evaluation = 50 questions, 2 points each (100 total)
- 📦 Download sets as a zip bundle
- 🔍 Lookup evaluations by UUID
- 🧮 Score logging and pass/fail detection
- ☁️ Optional Google Sheets integration for results
- 🧠 Question Bank editing interface (add/delete/section view)

---

## 🗂️ File Structure

```plaintext
bm-evaluation-app/
├── app.py
├── users.json
├── questions_grouped.json
├── History/
├── static/
│   └── style.css (optional)
├── templates/
│   ├── login.html
│   ├── dashboard.html
│   ├── generate.html
│   ├── lookup.html
│   ├── results.html
│   ├── questions.html
│   └── section_questions.html
└── README.md
