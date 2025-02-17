Personal Finance Visualizer 💰📊
A web application to track expenses, visualize transactions, and set budgets efficiently. Built using MERN stack (MongoDB, Express, React, Node.js) with Socket.io, Tailwind CSS, and Recharts for real-time updates and data visualization.

Features 🚀
✅ Add, view, and delete transactions
✅ Set and update budgets by category
✅ View monthly and category-wise expenses in charts
✅ Compare expenses with budgets
✅ Real-time updates using Socket.io

Tech Stack 🛠️
Frontend: React (Vite), Tailwind CSS, shadcn/ui, Recharts
Backend: Node.js, Express.js, MongoDB, Mongoose
Other: Axios, Socket.io, dotenv
Installation & Setup 🏗️
1. Clone the Repository
sh
Copy
Edit
git clone https://github.com/your-username/finance-visualizer.git
cd finance-visualizer
2. Setup Backend
sh
Copy
Edit
cd server
npm install
Create a .env file inside the server folder and add:
ini
Copy
Edit
MONGO_URI=your_mongodb_connection_string
PORT=5000
Start the backend server:
sh
Copy
Edit
npm start
3. Setup Frontend
sh
Copy
Edit
cd ../client
npm install
npm run dev
The frontend will run at http://localhost:5173/

Deployment 🌍
Frontend: Deploy on Vercel
Backend: Deploy on Render
Contributing 🛠️
Feel free to open issues and submit pull requests!
