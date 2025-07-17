💸 Budget Tracker Frontend
A React-based frontend that connects to a Node.js + MongoDB backend, allowing users to track and view personal expenses in real time.

🚀 Live Demo
This app runs locally and connects to a backend API on localhost:5000.

🔧 How It Works
React hooks (useState, useEffect) manage frontend state and handle API interactions.
The frontend fetches expense data from the backend (GET /api/expenses) and displays it in a clean list.
Users can submit new expenses via a form, which triggers a POST request to the backend (POST /api/expenses).
Once saved in MongoDB, the new expense is immediately shown on screen.

🧱 Project Structure
budget-frontend-react/ ├── src/ │ ├── App.js # Main component (form + expense list) │ ├── index.js # React root │ ├── App.css # Basic styling │ └── ... ├── public/ │ └── index.html # HTML template ├── package.json # Project config and dependencies ├── README.md

🧪 Sample Data Flow
Frontend form submits:

{
  "title": "Coffee",
  "amount": 3.75,
  "category": "Food",
  "note": "Iced vanilla latte"
}

Sent to backend:
POST http://localhost:5000/api/expenses
Backend responds:
New expense document saved in MongoDB and returned to frontend → displayed live.

A React-based frontend that connects to a Node.js + MongoDB backend, allowing users to track and view personal expenses in real time.

---


🛠️ Built With
- React
- Fetch API
- Node.js + Express (Backend)
- MongoDB Compass

🗂️ Backend Repo
🔗 budget-backend

🧠 What I Learned
- How to connect a frontend to a REST API using fetch
- Managing form state and re-rendering dynamically with React
- Handling asynchronous data with useEffect and error logging
- Structuring a full-stack project for clean collaboration and deployment

💡 Next Steps
- Add form validation and error messages
- Style the UI with Tailwind or styled-components
- Add charts or summary stats using Chart.js or Recharts
- Deploy the frontend to Vercel or Netlify

## 📸 Screenshots

Here’s what the app looks like in action:

![App Screenshot](./screenshot.png)