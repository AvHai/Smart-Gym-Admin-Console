# 🏋️‍♂️ Smart Gym Admin Console

A modern, AI-powered admin dashboard to streamline gym operations, improve member experience, and optimize decision-making using intelligent insights.

---

## 🚀 Features

✅ **AI-Powered Member Insights** – Predict member churn and suggest retention strategies using ML models.  
✅ **Smart Equipment Monitoring** – AI predicts equipment maintenance needs to avoid breakdowns.  
✅ **Attendance Predictions** – Forecast peak hours and optimize staff schedules with AI.  
✅ **Member & Staff Management** – Add, update, or remove profiles securely.  
✅ **Class Scheduling** – Organize and manage fitness class schedules easily.  
✅ **Analytics Dashboard** – Visualize real-time data on memberships, revenue, and usage patterns.  
✅ **Secure Authentication** – JWT-based role-based access control.  
✅ **Responsive UI** – Works seamlessly across devices.

---

## 🤖 AI Integration

The console integrates a custom **Flask API** that serves Machine Learning models for:

- 🧠 **Predictive Analytics** – Member attendance, revenue forecasting.  
- 🔧 **Preventive Maintenance** – Detect anomalies in equipment usage patterns.  
- 📊 **Data-driven Recommendations** – Personalized class or workout suggestions for members.

---

## 🛠️ Tech Stack

- **Frontend:** React.js, Tailwind CSS, ShadCn library  
- **Backend:** Node.js, Express.js  
- **AI/ML API:** Flask, Scikit-learn, TensorFlow  
- **Database:** MongoDB  
- **Authentication:** JWT, bcrypt

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/your-username/smart-gym-admin-console.git
cd smart-gym-admin-console

# Frontend setup
cd client
npm install

# Backend setup
cd backend
npm install

# Start backend
npm run dev

# Start frontend
cd ../client
npm start
