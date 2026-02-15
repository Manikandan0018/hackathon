Personalized Academic Skill-Gap Analysis System

An intelligent MERN stack application designed to help students evaluate their readiness for future courses by detecting skill gaps, generating personalized study plans, and tracking progress dynamically.

📌 Overview

Students often enroll in advanced courses without clearly understanding whether they meet prerequisite requirements. This project solves that problem by providing an academic-specific skill analysis engine.

The system compares:

✔ Student’s known skills
✔ Faculty-defined course prerequisites

Then generates:

✔ Missing skill insights
✔ Human-readable suggestions
✔ Adaptive study guidance
✔ Real-time readiness tracking

🎯 Problem Statement

Students lack an automated way to:

• Assess course readiness
• Identify missing competencies
• Receive structured study guidance
• Track learning progress

This leads to academic difficulty, inefficient preparation, and poor decision-making.

✅ Solution

The Personalized Academic Skill-Gap Analysis System provides:

• Skill-gap detection based on course requirements
• Personalized learning suggestions
• Study plan generation based on availability
• Topic / skill-wise completion tracking
• Real-time readiness score updates
• Faculty-driven prerequisite modeling

✨ Key Features

✔ User Authentication (JWT + bcrypt)
✔ Student Skill Input
✔ Course Selection
✔ Skill-Gap Analysis Engine
✔ Missing Skills Identification
✔ Study Plan Suggestions
✔ Mark Skills / Topics Complete
✔ Live Readiness Score Updates
✔ Responsive Modern UI

🧠 Innovation

Unlike generic AI tools, this system is:

✅ Curriculum-aware (faculty-defined prerequisites)
✅ Academic-specific (structured course intelligence)
✅ Personalized (student skill mapping)
✅ Adaptive (availability-driven study planning)
✅ Continuous (real-time progress feedback loop)

🛠 Technology Stack

Frontend:
• React.js
• Tailwind CSS
• GSAP Animations

Backend:
• Node.js
• Express.js

Database:
• MongoDB

Authentication:
• JWT
• bcrypt

Optional AI Integration:
• LLM / Rule-Based Study Plan Logic

🗂 Project Structure
backend/
│── server.js
│── config/
│── models/
│── routes/
│── controllers/
│── middleware/
│── utils/

frontend/
│── src/
│── components/
│── pages/
│── App.jsx

⚙️ Installation & Setup
1️⃣ Clone Repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

2️⃣ Backend Setup
cd backend
npm install


Create .env file:

PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key


Run backend:

npm run dev

3️⃣ Frontend Setup
cd frontend
npm install
npm run dev

🔄 System Workflow

User logs into system

Student enters known skills

Student selects target course

Backend compares prerequisites vs skills

Missing skills identified

Readiness score calculated

Study guidance generated

Student marks skills complete

Progress updates dynamically

📊 Expected Outcomes

✔ Improved course readiness awareness
✔ Personalized academic guidance
✔ Efficient study planning
✔ Reduced learning difficulty
✔ Better educational decision-making

🔮 Future Enhancements

• Advanced AI Study Plan Engine
• Topic-Level Learning Modules
• Smart Time Allocation System
• Faculty Analytics Dashboard
• Skill Certification Tracking
