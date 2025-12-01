<div align="center">

  
  
  <h1>HiQuiz</h1>
  
  <p>
    <strong>A high-performance, scalable Knowledge Assessment Platform designed for real-time evaluation.</strong>
  </p>

  <p>
    <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React">
    <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" alt="NodeJS">
    <img src="https://img.shields.io/badge/mongodb-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
    <img src="https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB" alt="Express">
    <img src="https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens" alt="JWT">
  </p>
</div>

<br />

## 💡 The Problem & Solution
Traditional evaluation methods are often static and lack engagement. **HiQuiz** modernizes assessment by providing a responsive, gamified interface that handles real-time scoring and user tracking.

It is designed not just as a quiz app, but as a modular **Evaluation Engine** capable of scaling from a simple trivia game to a corporate training assessment tool.

---

## 📸 Application Interface

> **Note for Recruiters:** The application features a fully responsive design optimized for mobile and desktop viewports.

<div align="center"> 
  <img src="./dashboard-preview-2.png" alt="Dashboard" style="border-radius: 10px; box-shadow: 0px 4px 10px rgba(0,0,0,0.1);"/>
</div>

---

## 🔥 Key Technical Features

### **Core Functionality**
* **Robust Authentication:** Secure JWT-based login/signup with session management.
* **Dynamic Quiz Engine:** Fetches questions efficiently from the database with randomized ordering.
* **Real-time Feedback:** Immediate answer validation and score calculation without page reloads.

### **Advanced Implementation**
* **State Management:** Utilized [Redux/Context API] to manage complex user states across the quiz lifecycle.
* **Performance Optimization:** Implemented lazy loading for components to reduce Initial Load Time (TTI) by [X]%.
* **RESTful API Architecture:** Designed scalable endpoints adhering to strict REST principles.

---

## 🧠 Engineering Challenges & Learnings

* **Handling State Persistence:** * *Challenge:* Losing quiz progress upon page refresh.
    * *Solution:* Implemented `localStorage` synchronization with the Redux store to ensure user progress is saved locally until submission.
* **Scalable Database Schema:**
    * *Challenge:* Designing a schema that allows for different question types (MCQ, Boolean, Text).
    * *Solution:* Used a polymorphic association strategy in MongoDB to allow flexible document structures for questions.

---

## 💻 Local Setup Guide

Follow these instructions to set up the project locally for development and testing purposes.

**1. Clone the repository**
```bash
git clone [https://github.com/anupam-iiitm/HiQuiz.git](https://github.com/anupam-iiitm/HiQuiz.git)
cd HiQuiz
