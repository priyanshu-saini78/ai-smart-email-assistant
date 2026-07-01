# 🤖 AI Smart Email Assistant

An AI-powered Email Assistant built using **n8n** and **Google Gemini AI** that automatically classifies incoming emails, analyzes their priority and sentiment, generates professional replies, and automates email workflows.

---

## 📌 Project Overview

This project automates email management using Artificial Intelligence. Instead of manually reading and replying to every email, the workflow analyzes each incoming email and generates an intelligent response.

The workflow is designed using **n8n** and integrates **Google Gemini AI**, **Gmail**, and **Google Sheets** to streamline email handling.

---

## ✨ Features

- 📧 Automatically reads incoming Gmail messages
- 🤖 Classifies emails into categories
- ⭐ Detects email priority (High / Medium / Low)
- 😊 Performs sentiment analysis
- 📝 Generates professional AI replies
- 📊 Stores email details in Google Sheets
- ✅ Sends replies only when required
- ⚡ Fully automated workflow using n8n

---

## 🛠 Tech Stack

- n8n
- Google Gemini AI
- Gmail
- Google Sheets
- AI Agent
- Structured Output Parser
- Webhooks

---

## 🔄 Workflow

```text
Gmail Trigger
      │
      ▼
Edit Fields
      │
      ▼
AI Agent (Google Gemini AI)
      │
      ▼
Structured Output Parser
      │
      ▼
IF Node
   ├── Reply Required → Gmail Reply → Google Sheets
   └── No Reply → Google Sheets
```

---

## 📸 Screenshots

### Workflow

> Add your workflow screenshot here.

Example:

```
screenshots/workflow.png
```

---

## 🚀 How It Works

1. Gmail Trigger detects a new email.
2. Required email fields are extracted.
3. Google Gemini AI analyzes the email.
4. AI identifies:
   - Category
   - Priority
   - Sentiment
   - Summary
   - Reply Requirement
5. If a reply is required:
   - AI generates a professional response.
   - Gmail sends the reply automatically.
6. Email details are stored in Google Sheets.

---

## 📂 Repository Structure

```
ai-smart-email-assistant/
│
├── workflow.json
├── README.md
└── screenshots/
    └── workflow.png
```

---

## 🎯 Future Improvements

- Support multiple AI models
- Spam detection
- Attachment summarization
- Multi-language email replies
- Calendar integration
- CRM integration

---

## 👨‍💻 Author

**Priyanshu Saini**

- GitHub: https://github.com/priyanshu-saini78
- LinkedIn: https://www.linkedin.com/in/priyanshusaini-ai/

---

⭐ If you found this project useful, consider giving it a star.
