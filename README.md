# AI Resume Enhancer

**AI Resume Enhancer** is a free, web-based tool that helps users improve their resumes through intelligent, automated feedback. Upload your resume (PDF or image) and receive actionable suggestions on formatting, grammar, readability, and design — powered by AI.

## ✨ Features

- Upload support for **PDF**, **JPG**, and **PNG** formats  
- **AI-generated feedback** on structure, clarity, and grammar  
- **Resume quality rating** with detailed breakdown  
- Highlights key **issues and improvement areas**  
- **Mobile-friendly UI** with clean, responsive design (Tailwind CSS)

## 🚀 Live Demo

- 🌐 Web App: [https://airesume-enhancer.netlify.app/](https://airesume-enhancer.netlify.app/)
- 🧠 API Endpoint: [https://ai-resume-checker-nxhw.onrender.com](https://ai-resume-checker-nxhw.onrender.com)

## 📦 Technologies Used

- **Frontend**: HTML, Tailwind CSS, JavaScript (Vanilla)
- **Backend**: Node.js, Express, Multer
- **AI Model**: Google Gemini API (or equivalent LLM)
- **Hosting**: Netlify (Frontend), Render (Backend)

## 📄 API Response Format

The API returns structured JSON feedback:

```json
{
  "sessionID": "abc123",
  "feedback": "Your resume is well-structured but lacks quantifiable metrics and consistent formatting.",
  "rating": "7.5/10",
  "issues": [
    "lacks quantifiable metrics",
    "consistent formatting"
  ]
}
