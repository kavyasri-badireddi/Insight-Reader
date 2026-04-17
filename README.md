
 📄 DocReader – AI-Powered Document Chat Application

DocReader is a full-stack web application that allows users to upload documents and interact with them using AI-powered chat. It extracts meaningful insights from documents and enables conversational querying for better understanding.



🚀 Features

* 📂 Upload and manage documents
* 💬 Chat with your documents using AI
* 🔐 User authentication (login/signup)
* 🧠 Smart text chunking & embeddings
* 📜 Chat history tracking
* ⚡ Fast and responsive UI



🏗️ Tech Stack

 # Frontend

* React (Vite)
* CSS
* Axios (API calls)

# Backend

* Node.js
* Express.js
* MongoDB (Mongoose)
* JWT Authentication

# AI/Processing

* Embedding service
* Chunking service
* AI response generation



 📁 Project Structure

```
DocReader/
│
├── backend/
│   ├── config/         # Database connection
│   ├── middleware/     # Auth middleware
│   ├── models/         # Mongoose schemas
│   ├── routes/         # API routes
│   ├── services/       # AI, embeddings, chunking
│   └── server.js       # Entry point
│
├── frontend/
│   ├── src/
│   │   ├── components/ # UI components
│   │   ├── api.js      # API integration
│   │   ├── App.jsx     # Main app
│   │   └── main.jsx    # Entry point
│   └── index.html
│
└── README.md
```



# ⚙️ Installation & Setup

#  1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/docreader.git
cd docreader
```



# 2️⃣ Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file in the backend folder:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
OPENAI_API_KEY=your_api_key
```

Run the backend:

```bash
npm start
```



# 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```



# 🔐 Authentication

* Users must sign up/login to access document chat
* JWT is used for secure authentication
* Protected routes ensure data privacy



# 🧠 How It Works

1. User uploads a document
2. Document is split into chunks
3. Each chunk is converted into embeddings
4. User asks a question
5. Relevant chunks are retrieved
6. AI generates a contextual answer



# 📡 API Endpoints

# Auth

* `POST /api/auth/register`
* `POST /api/auth/login`

# Documents

* `POST /api/docs/upload`
* `GET /api/docs`

# Chat

* `POST /api/chat`
* `GET /api/chat/history`



# 📸 Screens (Optional)

You can add screenshots here later:

```
![Upload UI](./screenshots/upload.png)
![Chat UI](./screenshots/chat.png)
```



# 🛠️ Future Improvements

* 📄 Support for more file formats (PDF, DOCX)
* 🔍 Semantic search optimization
* 🌐 Multi-language support
* 📊 Analytics dashboard
* ☁️ Cloud storage integration



# 🤝 Contributing

Contributions are welcome!

```bash
fork → clone → create branch → commit → push → PR
```

---

## 📜 License

This project is licensed under the MIT License.



## 👨‍💻 Author

Your Name
GitHub: [(https://github.com/kavyasri-badireddi)]


