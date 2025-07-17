# 💸 Budget Tracker Frontend

A React-based frontend that connects to a Node.js + MongoDB backend, allowing users to track and manage personal expenses in real time.

---

## 🚀 Live Demo

> _This app runs locally and connects to a backend API on `http://localhost:5000`._

---

## 🔧 How It Works

- React hooks (`useState`, `useEffect`) manage frontend state and API interactions.
- The app fetches expense data via a GET request to `http://localhost:5000/api/expenses`.
- A form allows users to submit new expenses via a POST request to the same endpoint.
- Submitted data is stored in MongoDB and immediately reflected on the UI.

---

## 🧱 Project Structure

budget-frontend-react/ ├── src/ │   ├── App.js            # Main component: form + expense list │   ├── App.css           # Basic styling │   ├── index.js          # Entry point │   └── ... ├── public/ │   └── index.html        # HTML shell ├── package.json          # App configuration ├── README.md             # Documentation ├── screenshot.png        # UI preview image

---

## 🧪 Sample Data Flow

Frontend form submission:

```json
{
  "title": "Coffee",
  "amount": 3.75,
  "category": "Food",
  "note": "Iced vanilla latte"
}

POST http://localhost:5000/api/expenses

🛠️ Built With
- React
- Fetch API
- Node.js + Express (Backend)
- MongoDB + Mongoose
- MongoDB Compass

📂 Related Repositories
- 🔗 Budget Backend

📸 Screenshots
Here’s what the app looks like in action:
App Screenshot

🧠 What I Learned
- Connecting a React frontend to a REST API
- Managing state with hooks and updating lists dynamically
- Debugging CORS and environment variables across client/server
- Git and GitHub workflows for organizing full-stack apps

💡 Next Steps
- ✅ Add form validation and toast feedback
- 🎨 Improve UI with Tailwind or styled-components
- 📊 Integrate charts using Chart.js or Recharts
- 🌍 Deploy to Vercel or Netlify for public access

🤝 Contributing & Feedback
Pull requests welcome!
Find me at github.com/kuurbe to follow my projects and progress.
