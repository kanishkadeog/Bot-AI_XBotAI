# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

--------------------------------------------------------------------------------------------------------------------------


# 🤖 XBotAI – Chat with Soul AI

XBotAI is a responsive, interactive chat interface built using **ReactJS** that allows users to chat with an AI model, give real-time feedback, and revisit previous conversations. This project was created as part of a 10-hour frontend assessment challenge.

---
## 🔗 Live Demo
[Click here to view the live app](https://xbotai-hqabzvmdn-kanishkas-projects-95e27a37.vercel.app/)


## 🚀 Features

- 🧠 **Chat Interface** with simulated AI responses
- 👍👎 **Like/Dislike Feedback** on AI messages (visible on hover)
- ⭐ **5-Star Rating & Feedback Form** at the end of each conversation
- 💾 **Save Conversations** and revisit via `/history` route
- 🕓 **Conversation History View**
- 📊 **Feedback Summary View** with rating filter
- 📱 **Responsive Design** for mobile/tablet/desktop
- ✅ **Assessment Ready** (passes all automated test cases)

---

## 📸 Screenshots

Chat AI Page :-
![image](https://github.com/user-attachments/assets/bfe70582-72c5-4f99-88f1-c497c4b4205d)


Feedback & rating :-
![image](https://github.com/user-attachments/assets/8ce57ed3-3764-435c-94cc-d61dd10641a4)


History Page :-
![image](https://github.com/user-attachments/assets/45ce56d8-5f69-4425-8527-d4542fe6d11e)




---

## 🛠️ Tech Stack

- ReactJS
- HTML5, CSS3
- JavaScript (ES6+)
- React Router DOM

---

## 📂 Folder Structure

## 📂 Folder Structure
src/
│
├── assets/
├── aiData/
│     └── sampleData.json
├── components/
│     ├── ChatFilter/
│     │     └── ChatFilter.jsx
│     ├── ChatHistoryCard/
│     │     └── ChatHistoryCard.jsx
│     ├── ChatInput/
│     │     └── ChatInput.jsx
│     ├── ChattingCard/
│     │     └──ChattingCard.jsx
│     ├── FeedbackModal/
│     │     └── FeedbackModal.jsx
│     ├── InitialChat/
│     │     ├── Card.jsx
│     │     └── InitialChat.jsx
│     ├── Navbar/
│     │     └── Navbar.jsx
│     └── sidebar/
│           └── sidebar.jsx
├── Pages/
│     ├── History/
│     │     └── History.jsx
│     └── Home/
│           └── Home.jsx
├── theme/
│     ├── ThemeContext.jsx
│     └── ThemePallete.jsx
├── App.js
├── index.css
├── index.js
└── style.css
