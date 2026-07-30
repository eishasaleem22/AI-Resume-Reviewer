# 🤖 AI Resume Reviewer

An AI-powered Resume Reviewer built using **n8n**, **Google Gemini**, and **Gmail**.

## 📌 Features

- 📄 Upload a PDF resume
- 🤖 AI-powered resume analysis using Google Gemini
- 📊 ATS Score generation
- 📝 Professional summary
- ✅ Strengths identification
- ⚠️ Weaknesses detection
- 📚 Missing skills analysis
- 💡 Personalized improvement suggestions
- 📧 Automatically sends a beautiful HTML email report

---

## 🛠️ Tech Stack

- n8n
- Google Gemini
- JavaScript
- Gmail
- PDF Extract

---

## 🔄 Workflow

```text
Resume Upload
      ↓
Extract PDF
      ↓
Google Gemini Analysis
      ↓
Generate ATS Score & Feedback
      ↓
Create HTML Email
      ↓
Send Email via Gmail
```

---

## 📂 Repository Contents

- `AI Resume Reviewer.json` → Complete n8n workflow

---

## 🚀 How to Use

1. Import the `AI Resume Reviewer.json` workflow into n8n.
2. Configure your Google Gemini API credentials.
3. Configure your Gmail credentials.
4. Run the workflow.
5. Upload a PDF resume through the form.
6. Receive an AI-generated resume review by email.

---

## 📜 License

This project is licensed under the MIT License.
