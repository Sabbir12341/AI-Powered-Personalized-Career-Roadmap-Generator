# Guider - AI Career Roadmap Generator

An intelligent **n8n** workflow that collects user information and automatically generates a **personalized career roadmap** in **Bangla** using Google Gemini AI.

---

## ✨ Overview

**Guider** is a smart automation system that helps users get professional career guidance. Users fill out a simple form with their details and chosen profession, and the system instantly generates a complete, structured, and actionable career roadmap — all stored neatly in Airtable.

---

## 🚀 Features

- **Professional Web Form** with validation
- **Multi-Profession Support** (Programmer, Designer, AI Automation Expert)
- **AI-Powered Roadmap Generation** using Google Gemini
- **Bangla Language Output** – Simple and easy to understand
- **Automatic Data Storage** in Airtable
- **Fully Automated** workflow
- Clean, structured, and motivational career guidance

---

## 📋 How It Works

1. User submits the form with personal details and profession
2. Data is saved to **Airtable**
3. **AI Agent** analyzes the input and generates a personalized roadmap
4. The generated roadmap is automatically updated back to the Airtable record

---

## 📝 Form Fields

- **Name** (Required)
- **Email** (Required)
- **Phone** (Required)
- **Summary** – Tell us about yourself (Required)
- **Profession** – Dropdown selection:
  - Programmer
  - Designer
  - AI Automation Expert

---

## 📊 What the AI Generates

- Warm greeting using the user's name
- Profession overview (demand, opportunities, future scope)
- Step-by-step roadmap:
  - Beginner Level
  - Intermediate Level
  - Advanced Level
- Recommended portfolio projects
- Tools, technologies & learning resources
- Timeline plan (3, 6 & 12 months)
- Immediate actionable next steps

---

## 🛠️ Technologies Used

- **n8n** – Workflow Automation
- **Google Gemini** – AI Model (via LangChain)
- **Airtable** – Database
- **LangChain** – AI Agent Framework

---

## 📥 Installation & Setup

1. Download the workflow file: `Guider.json`
2. In n8n, go to **Workflows** → **Import from File**
3. Import the JSON file
4. Set up credentials:
   - **Airtable Personal Access Token**
   - **Google Gemini API Key**
5. Update Airtable Base & Table IDs (if needed)
6. Activate the workflow

---

## 🧪 How to Use

1. Open the workflow and get the **Form Trigger URL**
2. Share the form with users
3. After submission, check your Airtable base — the roadmap will appear in the "Roadmap" column

---

## 📸 Screenshots

*(Add screenshots here: Form, Airtable records, Sample Roadmap)*

---

## 🔮 Future Enhancements

- Add more professions
- Email delivery of roadmap (PDF format)
- WhatsApp/Telegram notification
- Progress tracking system
- Certificate generation

---

## 📄 License

This project is open-source under the **MIT License**.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to fork and improve.

---

**Made with ❤️ for aspiring professionals in Bangladesh**

---

*Give this project a ⭐ if it helped you or your community!*
