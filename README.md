# 🎙️ AI Meeting Summarizer and Action Manager

An AI-powered web application designed to simplify online meetings by combining video conferencing, live speech transcription, AI-generated meeting summaries, and task management. The application provides separate dashboards for managers and employees, enabling efficient collaboration and meeting documentation.

---

## 📌 Project Overview

Managing meetings often involves manually taking notes, tracking discussions, and assigning tasks. This project automates these processes by integrating meeting management with AI-based transcript summarization.

The application allows users to:

- Conduct online meetings using Jitsi Meet
- Record meeting audio
- Generate live speech-to-text transcripts
- Summarize meeting transcripts using Ollama LLM
- Manage employee tasks
- Export reports in PDF and PowerPoint format

---

# ✨ Features

## 👥 Role-Based User Interface

- Manager Dashboard
- Employee Dashboard
- Separate functionalities for each role

---

## 🎥 Online Meeting Integration

- Jitsi Meet integration
- Create and join virtual meetings
- Browser-based video conferencing

---

## 🎤 Audio Recording

- Record microphone audio
- Record meeting audio
- Download recorded audio files

---

## 📝 Live Speech-to-Text

- Real-time speech recognition
- Automatic transcript generation
- Download transcript as a text file

---

## 🤖 AI Transcript Summarization

Uses **Ollama Local LLM** to generate:

- Brief summaries
- Detailed summaries
- Bullet-point summaries
- Action-item summaries
- Q&A summaries
- Custom prompt summaries

---

## 📋 Task Management

Manager can:

- Assign tasks
- Track employee progress
- Monitor completion status

Employee can:

- View assigned tasks
- Update progress
- Mark tasks as completed

---

## 📄 Report Generation

Export meeting information as:

- PDF
- PowerPoint
- Text Transcript

---

# 🛠️ Technologies Used

## Frontend

- HTML5
- CSS3
- JavaScript (ES6)

## AI

- Ollama
- Llama 3.2
- Mistral
- Qwen 2.5

## Browser APIs

- MediaRecorder API
- Web Speech API
- FileReader API

## Meeting Platform

- Jitsi Meet External API

## Storage

- Browser Local Storage

---

# 📂 Project Structure

```
Project
│
├── index.html
├── manager.html
├── employee.html
├── meeting.html
├── summarizer.html
├── css/
├── js/
├── assets/
└── README.md
```

---

# 🚀 How It Works

```
Manager Starts Meeting
            │
            ▼
      Jitsi Meeting
            │
            ▼
     Audio Recording
            │
            ▼
 Live Speech Recognition
            │
            ▼
      Transcript File
            │
            ▼
      Ollama AI Model
            │
            ▼
 AI Generated Summary
            │
            ▼
 Download Summary / Reports
```

---

# 💻 Installation

## Clone Repository

```bash
git clone https://github.com/your-username/AI-Meeting-Summarizer.git
```

---

## Open Project

Open the project in **Visual Studio Code**.

---

## Start Ollama

Install Ollama from:

https://ollama.com/

Pull a supported model:

```bash
ollama pull llama3.2
```

or

```bash
ollama pull mistral
```

Run Ollama:

```bash
ollama serve
```

Default API:

```
http://localhost:11434
```

---

## Launch Application

Open:

```
index.html
```

in your browser.

---

# 📸 Application Modules

### Login Page

- Manager Login
- Employee Login

### Manager Dashboard

- Manage employees
- Assign tasks
- Start meetings
- Generate reports

### Employee Dashboard

- View assigned tasks
- Join meetings
- Update task progress

### Meeting Module

- Video conferencing
- Audio recording
- Speech recognition

### AI Summarizer

- Upload transcript
- Generate AI summary
- Download summary

---

# 📈 Future Enhancements

Planned improvements include:

- JWT Authentication
- Node.js & Express Backend
- MongoDB Database
- Secure User Authentication
- Automatic AI Task Assignment
- Real-time Notifications
- Meeting History
- Cloud Deployment
- Email Notifications
- REST APIs

---

# 🎯 Learning Outcomes

Through this project, I gained practical experience with:

- AI-powered applications
- Browser Media APIs
- Speech Recognition
- Local Large Language Models (LLMs)
- Jitsi Meet integration
- JavaScript DOM manipulation
- Task management systems
- Client-side data management

---

# 📌 Current Limitations

- Uses Local Storage for data persistence
- Client-side authentication
- No backend server
- No JWT authentication
- No database integration

These features are planned for future versions.

---

# 👨‍💻 Author

**Thejas Naika**

Bachelor of Engineering – Computer Science and Engineering (AI&ML)

---

# ⭐ If you found this project useful, consider giving it a Star!
