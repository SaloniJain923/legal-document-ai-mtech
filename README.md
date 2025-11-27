# ⚖️ LexiLegal AI – AI-Powered Legal Document Analyzer & Summarizer

LexiLegal AI is a full-stack AI-based legal analysis platform designed to simplify contract review and legal document understanding. It enables users to upload PDF/DOCX files and receive AI-generated summaries, extracted entities, highlighted clauses, and structured insights in real time.

---

## 🌐 Project Links

| Component | Live Link |
|----------|-----------|
| 🌍 Website (Frontend - React) | https://your-frontend-deployment-link.com |
| 🛠 Backend API (Node.js / Express) | https://your-backend-api-link.com |
| 🤖 AI Microservice (Python NLP) | https://your-ai-engine-url.com |
| 🗄 Database (MongoDB Atlas Dashboard) | https://cloud.mongodb.com |
---

## 🚀 Key Features
- Upload & analyze PDF / DOCX legal documents
- Transformer-based AI summarization
- Legal Named Entity Recognition (NER)
- Clause classification (Rights, Obligations, Penalties, etc.)
- Secure JWT authentication and encrypted storage
- Visual entity highlighting and clause grouping
- Export summaries in PDF / DOCX
- Dashboard with document history
- Fully responsive advanced UI / dark mode
- AI chat assistant for legal query support

---

## 📡 API Endpoints

| Feature              | Method | Endpoint                                                         |
|----------------------|--------|-------------------------------------------------------------------|
| **Register User**    | POST   | `http://localhost:5000/api/auth/register`                        |
| **Login User**       | POST   | `http://localhost:5000/api/auth/login`                           |
| **Get Profile**      | GET    | `http://localhost:5000/api/auth/profile`                         |
| **Update Profile**   | PUT    | `http://localhost:5000/api/auth/profile/update`                  |
| **Change Password**  | PUT    | `http://localhost:5000/api/auth/change-password`                 |
| **Delete Account**   | DELETE | `http://localhost:5000/api/auth/delete`                          |
| **Upload Document**  | POST   | `http://localhost:5000/api/documents/upload`                     |
| **Get All Documents**| GET    | `http://localhost:5000/api/documents`                            |
| **Get Document**     | GET    | `http://localhost:5000/api/documents/:id`                        |
| **Delete Document**  | DELETE | `http://localhost:5000/api/documents/:id`                        |
| **AI Summarization** | POST   | `http://localhost:5000/api/ai/summarize`                         |
| **AI Metadata**      | POST   | `http://localhost:5000/api/ai/extract-metadata`                  |
| **Search Documents** | GET    | `http://localhost:5000/api/search/documents/search?q=query`      |

---

## 🌍 Access the Application

| Service | URL |
|--------|-----|
| **Frontend** | https://legal-document-al-4gaq.vercel.app |
| **Backend API** | https://server-legal-doc.vercel.app/ |
| **Health Check** | https://server-legal-doc.vercel.app/health |


