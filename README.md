# FlashFocus

**FlashFocus** is a study tool designed to help learners absorb information more effectively. It generates summaries, interactive flashcards, and custom quizzes from your notes, making your study sessions more focused and productive. Perfect for students, professionals, and anyone looking to learn smarter!

## Features

- **Summarize Notes**: Input your study material, and FlashFocus will generate a concise summary to help you focus on the key points.
- **Flashcards**: Automatically generate flashcards based on your notes, making it easier to review important concepts.
- **Practice Quizzes**: Create multiple-choice or open-ended questions for practice and reinforce your learning.
- **User-Friendly Interface**: The app is built with **React** and **Node.js**, providing an intuitive, easy-to-use interface.
- **AI-Powered**: Leverages the **Gemini API** for summarization, flashcard generation, and quiz creation.

## Technologies Used

- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express
- **AI Integration**: Gemini API
- **Database**: MongoDB

## 🏗️ Installation & Setup
### Prerequisites
- Node.js (>=22.x)
- MongoDB (Local or Atlas)
- Gemini API Key

### Clone the Repository
```sh
 git clone https://github.com/mesametamaarkhan/theekkardo
 cd flash-focus
```

### Backend Setup
```sh
 cd backend
 npm install
 npm run dev
```

### Frontend Setup
```sh
 cd frontend
 npm install
 npm run dev
```
---

## 📌 Environment Variables
Create a `.env` file in the `server/` directory and add:
```sh
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_api_key
```

---

## 📬 Contact
For support or inquiries, contact **mesametamaarkhan@gmail.com** or open an issue in the repo.

