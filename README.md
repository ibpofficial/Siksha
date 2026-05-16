# Siksha
🌟 ShikshaSetu – AI Learning Assistant

🚀 Empowering teachers and students in low-resource environments with AI-powered literacy & numeracy learning tools.

📚 Overview

ShikshaSetu is an AI-powered educational platform designed to bridge foundational learning gaps for early-grade students (Grade 1–3).
It provides:

👩‍🏫 Teacher dashboards
👨‍🎓 Student learning portals
🤖 AI-generated quizzes & reports
📊 Performance analytics
🖨️ Printable offline worksheets
🌐 Multi-language support
☁️ Firebase-powered cloud storage

The platform is specially optimized for low-resource schools and rural education systems.

✨ Features
👩‍🏫 Teacher Dashboard
📈 Classroom analytics
👥 Student management
🧠 AI-powered performance reports
📚 Assignment creation
🎯 Learning gap identification
🏆 Student ranking system
📤 Parent SMS alerts (mock feature)
🖨️ Offline printable worksheets
👨‍🎓 Student Dashboard
🔐 Secure login system
📝 Interactive quizzes
⭐ Gamified learning experience
📊 Performance tracking
📚 Literacy & numeracy activities
🎖️ Reward-based engagement
🤖 AI Features
✅ AI Question Generation

Generate multiple-choice questions automatically using AI:

Topic-based quizzes
Difficulty selection
Multi-language support
Reading comprehension passages
✅ AI Student Analysis

The platform generates:

📌 Current standing reports
📉 Learning gap analysis
📚 Personalized interventions
🧩 Foundational skill recommendations

Powered using:

⚡ DeepSeek AI
🔗 OpenRouter API
🛠️ Tech Stack
Technology	Usage
HTML5	Structure
Tailwind CSS	UI Styling
JavaScript (ES6)	Logic
Firebase	Authentication & Database
Firestore	Cloud Storage
Chart.js	Data Visualization
Font Awesome	Icons
DeepSeek AI	AI Question Generation
OpenRouter API	AI Integration
🎨 UI/UX Highlights
🌈 Modern glassmorphism design
📱 Fully responsive interface
⚡ Smooth animations
🧊 Bento-style dashboard cards
🌙 Elegant gradients & shadows
🔔 Toast notifications
📊 Interactive analytics
🔥 Core Modules
1️⃣ Authentication System
Teacher Login
Username/password authentication
Admin dashboard access
Student Login
Student selector
Password-based secure access
2️⃣ Student Management

Teachers can:

➕ Add students
✏️ Edit credentials
❌ Remove students
🏫 Organize classrooms
📊 Monitor progress
3️⃣ Assignment System

Teachers can:

Create quizzes manually
Generate quizzes with AI
Assign to:
👥 Entire classroom
👤 Specific students

Includes:

Difficulty selection
Subject targeting
Printable worksheets
4️⃣ AI Reporting Engine

AI analyzes:

📈 Test scores
📚 Subject mastery
🧠 Learning trends

Outputs:

Personalized recommendations
Weakness detection
Home activity suggestions
☁️ Firebase Configuration

The app uses Firebase services:

🔐 Firebase Authentication
🗄️ Cloud Firestore

Example initialization:

const app = initializeApp(firebaseConfig);
const db = getFirestore(app);
const auth = getAuth(app);
📂 Project Structure
ShikshaSetu/
│
├── demo.html          # Main application file
├── assets/            # Static assets
├── firebase/          # Firebase configs
├── styles/            # Custom styles
├── scripts/           # JS modules
└── README.md
🚀 Getting Started
📥 Installation
1️⃣ Clone Repository
git clone https://github.com/your-username/shikshasetu.git
2️⃣ Navigate to Project
cd shikshasetu
3️⃣ Open in Browser

Simply open:

demo.html

OR run using VSCode Live Server.

🔑 Firebase Setup
Create Firebase project
Enable:
Authentication
Firestore Database
Replace config:
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
};
🤖 OpenRouter / DeepSeek Setup

Replace:

const DEEPSEEK_API_KEY = "YOUR_API_KEY";

⚠️ Never expose production API keys publicly.

📊 Dashboard Analytics

The system tracks:

📈 Student averages
🏆 Classroom rankings
📚 Subject mastery
⚠️ Weak student detection
✅ Assignment completion
🌍 Educational Impact

ShikshaSetu is designed to:

📚 Improve foundational literacy
🔢 Strengthen numeracy skills
🌐 Support local language learning
🏫 Empower under-resourced schools
👩‍🏫 Reduce teacher workload
🖨️ Offline Support

Teachers can:

Generate printable worksheets
Conduct offline assessments
Use in low-internet environments

Perfect for:

Rural schools
Community learning centers
NGO education programs
🔒 Security Notes

⚠️ Current demo version includes:

Client-side authentication
Embedded API references

For production:

Use secure backend APIs
Implement environment variables
Add Firebase security rules
Enable role-based access control
📸 Screens Included

✅ Teacher Dashboard
✅ Student Login
✅ AI Reports
✅ Assignment Management
✅ Printable Worksheets

🌟 Future Enhancements
📱 Mobile App
🎤 Voice-based learning
🌐 Regional language expansion
🧠 Adaptive AI tutoring
📶 Offline-first sync
🏅 Advanced gamification
📹 Video learning support
🤝 Contribution

Contributions are welcome!

Steps
Fork repository 🍴
Create feature branch 🌱
Commit changes 💾
Push branch 🚀
Open Pull Request 🎉
👨‍💻 Author

Developed with ❤️ for improving foundational education through AI.

📄 License

This project is licensed under the MIT License.

⭐ Support

If you like this project:

⭐ Star the repository
🍴 Fork it
🧑‍💻 Contribute
📢 Share with educators
