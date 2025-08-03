# PicSureAI 🎨

PicSureAI is an AI-powered image generation web app that lets users turn text prompts into stunning images using OpenAI’s DALL·E API. It’s a full-stack project featuring modern frontend and backend technologies with a responsive and sleek UI.

---

## 🔥 Features

- 🖼️ Generate images using text prompts
- 📤 Share creations with the community
- 🌐 Responsive UI built with Tailwind CSS
- 🔒 Secure .env API key setup
- 🚀 Full-stack integration with MongoDB

---

## 🛠️ Tech Stack

| Layer       | Tech                            |
|-------------|----------------------------------|
| Frontend    | React.js, Tailwind CSS, Vite     |
| Backend     | Node.js, Express.js              |
| Database    | MongoDB                          |
| AI Service  | OpenAI DALL·E API                |
| Deployment  | GitHub (currently), Vercel/Render (optional) |

---

## 🗂️ Project Structure

PicSureAI/
│
├── client/ → Frontend (React + Tailwind)
│ ├── src/
│ └── index.html
│
├── server/ → Backend (Node + Express)
│ ├── routes/
│ ├── controllers/
│ └── .env → (Contains API keys, not pushed to GitHub)
│
├── .gitignore
└── README.md

yaml
Copy
Edit

---

## 🚀 How to Run Locally

> **Step-by-step guide to get the app running on your machine**

### 1️⃣ Clone the repository
```bash
git clone https://github.com/dhanshreeborde/PicSureAI.git
cd PicSureAI
2️⃣ Set up the backend
bash
Copy
Edit
cd server
npm install
➡️ Create a .env file inside server/ with this:

ini
Copy
Edit
OPENAI_API_KEY=your-openai-key-here
3️⃣ Set up the frontend
bash
Copy
Edit
cd ../client
npm install
4️⃣ Run both servers in separate terminals:
bash
Copy
Edit
# Terminal 1
cd server
npm start

# Terminal 2
cd client
npm run dev
Your app should now be running at:
Frontend: http://localhost:5173
Backend: http://localhost:5000

💡 Inspiration
This project was created to explore how AI can enhance creativity and to learn full-stack development using modern tools. The goal is to build an intuitive and powerful platform for creators.

🧠 Future Enhancements
User authentication (OAuth)

Image download & like feature

Image gallery with filters

Deployment on Vercel + Render

🙋‍♀️ Author
Dhanshree Borde
GitHub | LinkedIn

⚠️ This project uses the OpenAI API. Make sure not to expose your API keys publicly. Add .env to your .gitignore file to keep it secure.

yaml
Copy
Edit

---

After adding this file, don’t forget to push it to GitHub:

```bash
git add README.md
git commit -m "Add complete README file"
git push
