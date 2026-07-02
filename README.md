# Chatbot_Genai_tools
# 🤖 Gemini AI Chatbot

A simple AI-powered chatbot built using **FastAPI**, **Google Gemini API**, and **HTML, CSS, and JavaScript**. The application provides a clean chat interface where users can enter prompts and receive AI-generated responses.

---

## 🚀 Features

* 💬 Interactive chatbot interface
* 🤖 Google Gemini AI integration
* ⚡ FastAPI backend
* 🌐 Simple HTML, CSS, and JavaScript frontend
* 🔄 REST API communication using Fetch API
* 📝 User prompt input
* 📤 AI-generated responses
* 🎨 Responsive dark-themed UI

---

## 🛠️ Tech Stack

### Backend

* Python 3.x
* FastAPI
* Google Gen AI SDK
* Uvicorn

### Frontend

* HTML5
* CSS3
* JavaScript (Fetch API)

---

## 📂 Project Structure

```text
Chatbot_googleaitools_genai/
│
├── main.py              # FastAPI backend
├── index.html           # Frontend UI
├── script.js            # JavaScript logic
├── requirements.txt     # Python dependencies
├── .env                 # API Key (not committed)
├── .gitignore
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/<repository-name>.git
cd <repository-name>
```

### 2. Create a virtual environment

Windows

```bash
python -m venv .venv
```

Activate it:

```bash
.venv\Scripts\activate
```

Linux/macOS

```bash
python3 -m venv .venv
source .venv/bin/activate
```

---

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Create a `.env` file

```env
GOOGLE_API_KEY=YOUR_GOOGLE_API_KEY
```

> **Important:** Never commit your API key or `.env` file to GitHub.

---

### 5. Run the backend

```bash
uvicorn main:app --reload
```

The API will be available at:

```
http://127.0.0.1:8000
```

Interactive API documentation:

```
http://127.0.0.1:8000/docs
```

---

### 6. Open the frontend

Open `index.html` in your browser or serve it using a local web server (such as the VS Code Live Server extension).

---

## 📡 API Endpoint

### POST `/chat`

#### Request

```json
{
  "prompt": "Explain Artificial Intelligence."
}
```

#### Response

```json
{
  "reply": "Artificial Intelligence (AI) is..."
}
```

---

## 📸 Application Workflow

1. User enters a prompt.
2. JavaScript sends the prompt to the FastAPI backend.
3. FastAPI forwards the request to the Google Gemini API.
4. Gemini generates a response.
5. The backend returns the response.
6. The frontend displays the AI's reply.

---

## 🔮 Planned Improvements

* ✅ Persistent chat history
* ✅ MongoDB integration
* ✅ Multiple chat sessions
* ✅ User authentication
* ✅ Streaming AI responses
* ✅ Markdown rendering
* ✅ Code syntax highlighting
* ✅ File upload support (PDF, DOCX, Images)
* ✅ Voice input/output
* ✅ Conversation search
* ✅ Responsive mobile interface

---

## 📦 Dependencies

* FastAPI
* Uvicorn
* Google Gen AI SDK
* Python Dotenv
* Pydantic

---

## 🤝 Contributing

Contributions, bug reports, and feature requests are welcome. Feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Developed by **Gol.D Luffy** as a learning project to explore AI application development using Google Gemini and FastAPI.
