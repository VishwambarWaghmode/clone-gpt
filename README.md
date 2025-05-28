# 🌐 Web Based AI Assistant App using Gemini Model

This is a web-based AI assistant built using the **Gemini Model** by Google, designed to provide intelligent, real-time assistance via a modern, responsive UI. The project uses **Next.js** and **assistant-ui** for the frontend and integrates the **Gemini Model** through a secure backend API. Deployment is handled seamlessly with **Vercel**.

---

## 🚀 Features

- 🧠 Real-time AI-powered chat interface
- 🎨 Beautiful UI built with `assistant-ui` components
- 🌐 Hosted on Vercel with blazing fast performance
- 🧾 Message history & response formatting (coming soon)

---

## 🛠️ Tech Stack

| Layer       | Technology                         |
|-------------|-------------------------------------|
| Frontend    | [Next.js](https://nextjs.org/), Tailwind CSS, assistant-ui |
| Backend     | [Node.js](https://nodejs.org/), Express, JWT |
| AI Model    | [Gemini Pro](https://makersuite.google.com/app) |
| Deployment  | [Vercel](https://vercel.com/) (Frontend), Render/Local (Backend) |

---

## 📁 Project Structure
│
├── frontend/ # Next.js frontend
│ ├── src/pages/ # Page components (chat, login, analyze)
│ ├── src/utils/ # API handlers
│ ├── src/styles/ # Global Tailwind CSS
│ └── public/ # Static assets
│
├── backend/ # Node.js Express backend
│ ├── routes/ # Auth, Chat, File routes
│ ├── controllers/ # Gemini controller
│ ├── uploads/ # Temporary file storage
│ ├── .env # Secrets and Gemini API key
│ └── index.js # Server entry point


---

## 🧠 How It Works

- Users log in and enter messages in a chatbot interface.
- Messages are sent securely to the backend.
- The backend queries the **Gemini model** using the Google AI Studio API.
- Responses are returned to the frontend and displayed in a styled chat bubble.
- Uploaded files are analyzed and summarized using the same Gemini pipeline.

---

## 🔧 Local Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/ai-gemini-assistant.git
   cd ai-gemini-assistant

