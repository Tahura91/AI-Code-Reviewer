
# 🤖 AI Code Reviewer

An intelligent code reviewer powered by Google Gemini 2.0 Flash. This tool analyzes source code, detects issues, suggests improvements, and helps developers write clean, scalable, and secure software.

## ✨ What It Does

AI Code Reviewer acts as a **senior code reviewer** with over 7 years of experience across:

- Frontend, Backend, and Full-Stack (MERN)
- App Development (Flutter, React Native)
- Golang & Blockchain (Solidity, Hyperledger)
- DevOps, Security, and DSA Optimization

It takes any code as input and:
- Detects bugs, anti-patterns, and performance issues
- Recommends best practices
- Suggests cleaner, scalable alternatives
- Points out vulnerabilities and inefficiencies
- Provides real-world refactored code examples

## 🧠 Powered By

- **AI Model:** [Google Gemini 2.0 Flash](https://ai.google.dev/)
- **Access Method:** Official Node.js SDK – `@google/generative-ai`

---

## 🛠 Tech Stack


- **Frontend: React.js**
- **Backend: Node.js, Express.js**
- **Google Gemini SDK** (`@google/generative-ai`)
- **dotenv** – Securely loads API keys
- **JavaScript (ES6)**

---

## 📦 How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/ai-code-reviewer.git
   cd ai-code-reviewer
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Add your Gemini API key to a `.env` file:
   ```
   GOOGLE_GEMINI_KEY=your-api-key-here
   ```

4. Import and use the module in your code:
   ```js
   const generateContent = require('./generateContent');
   const prompt = "Your code snippet here...";
   const review = await generateContent(prompt);
   console.log(review);
   ```

---

## 🚧 In Development

Here are a few features planned for future versions:
- 🔍 Syntax-aware code highlighting in responses
- 📁 Upload multiple files for review
- 🧪 Test coverage and unit test suggestions
- 🌐 Web UI for easy interaction

---

## 📬 Contact

Feel free to reach out if you're interested in contributing or want to give feedback:

- **LinkedIn:** [my profile](https://www.linkedin.com/in/tahura-hayath-483397243/)
- **Email:** tahurahayath0@gmail.com 

---

## ⭐ Like the Project?

If this project helped you or inspired you, please consider dropping a ⭐ on [GitHub]((https://github.com/Tahura91/AI-Code-Reviewer)). It helps a lot!

---


