# 🧠 Intelligent Tutoring System

An AI-powered web application designed to provide **personalized learning experiences** through **adaptive assessments** and **real-time feedback**. Built with modern web technologies, this system aims to enhance the educational journey for **students** and **educators** alike.

---

## 🚀 Features

- 🔁 **Adaptive Learning** – Tailors content based on individual student performance
- ⚡ **Real-time Feedback** – Provides immediate insights to guide learners
- 🧑‍🏫 **User Roles** – Supports both students and educators with role-specific functionalities
- 💻 **Modern UI** – Responsive and intuitive interface built with **Next.js** and **Tailwind CSS**
- 🔐 **Secure Authentication** – JWT-based token auth system
- 🔎 **AI + Search APIs** – Uses Together AI, Serper, and Helicone

---

## 🛠️ Tech Stack

| Layer        | Tech                              |
|--------------|-----------------------------------|
| **Frontend** | Next.js, React, Tailwind CSS      |
| **Backend**  | Node.js, Express.js               |
| **Auth**     | JWT (JSON Web Tokens)             |
| **Deployment**| Vercel / Heroku                  |
| **APIs**     | Together AI, Serper.dev, Helicone |

---

## 📁 Project Structure

```
├── app/                # Application logic and routing
├── components/         # Reusable UI components
├── public/             # Static assets
├── utils/              # Utility functions
├── .env                # Environment variables
├── package.json        # Project metadata and dependencies
├── tailwind.config.ts  # Tailwind CSS configuration
└── tsconfig.json       # TypeScript configuration
```


---

## ⚙️ Environment Variables

Create a `.env` file in your root directory and add:

```env
TOGETHER_API_KEY=your_together_ai_key
SERPER_API_KEY=your_serper_api_key
HELICONE_API_KEY=your_helicone_api_key
```
---
## 🧑‍💻 Getting Started

### ✅ Prerequisites

- Node.js v14 or higher  
- npm
---
## 🔧 Installation
```
# Clone the repository
git clone https://github.com/imishangrover/Intelligent-Tutor-System.git

# Navigate to the project directory
cd Intelligent-Tutor-System

# Install dependencies
npm install
```
---
## 🔨 Running the Application
```
# Start the development server
npm run dev
```
--- 
## 🤝 Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any features, enhancements, or bug fixes.
