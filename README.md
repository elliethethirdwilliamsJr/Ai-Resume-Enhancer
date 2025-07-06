# AI Resume Enhancer

AI Resume Enhancer is a web-based tool that helps users improve their resumes through smart, automated feedback. By uploading a resume (PDF or image), users receive detailed suggestions on formatting, grammar, readability, and overall structure — all powered by an AI backend.

## ✨ Features

- Upload support for PDF, JPG, PNG formats
- AI-generated feedback on resume content and structure
- Rating system for resume quality
- Highlighted issues and improvement areas
- Mobile-responsive design with Tailwind CSS

## 🚀 Live Demo

Check out the live version here: [https://ai-resume-checker-nxhw.onrender.com](https://ai-resume-checker-nxhw.onrender.com)

## 📦 Technologies Used

- **Frontend**: HTML, Tailwind CSS, Vanilla JavaScript
- **Backend**: Node.js, Express, Multer, Google Gemini API (or similar)
- **Hosting**: Render.com

## 📄 API Response Structure

Example JSON response from the backend:

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
