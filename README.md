# 🌍 AI Trip Planner (PlanGo)

PlanGo is an **AI-powered trip planning web application** that generates personalized travel itineraries using **Google Gemini AI**. Users can create trips, save them to Firebase, and view detailed plans including hotels and places to visit — all through a clean, modern UI.

---

## ✨ Features

- 🤖 **AI-Powered Itineraries**  
  Generate detailed, day-wise travel plans using Google Gemini AI.

- 🔐 **Google Authentication**  
  Sign in securely using Google OAuth.

- ☁️ **Firebase Integration**  
  Store and retrieve trips using Firebase Firestore.

- 🗺️ **Dynamic Trip Views**  
  View hotels, places to visit, and daily plans for each trip.

- 🎨 **Modern UI**  
  Built with TailwindCSS and reusable UI components.

---

## 🛠 Tech Stack

- **Frontend**: React + Vite  
- **AI**: Google Gemini AI  
- **Authentication**: Google OAuth  
- **Database**: Firebase Firestore  
- **Styling**: TailwindCSS  

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or later recommended)
- Firebase project
- Google Gemini API key
- Google OAuth Client ID

---

## 📦 Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/naiduvelamala/AI-TRIP-PLANNER.git
cd AI-TRIP-PLANNER
2️⃣ Install dependencies
npm install

3️⃣ Configure Environment Variables

Create a .env file in the project root:

VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id

VITE_GEMINI_API_KEY=your_gemini_api_key
VITE_GOOGLE_AUTH_CLIENT_ID=your_google_oauth_client_id
VITE_GOOGLE_PLACE=your_google_places_api_key


⚠️ Do not commit .env to GitHub

4️⃣ Run the application
npm run dev


Open your browser at:

http://localhost:5173

📂 Project Structure
PlanGo/
├── public/
├── src/
│   ├── components/        # Reusable UI components
│   ├── constants/         # App constants & AI prompts
│   ├── create-trip/       # Trip creation flow
│   ├── my-trips/          # User saved trips
│   ├── service/           # Firebase & Gemini integrations
│   ├── view-trip/         # Trip details view
│   ├── App.jsx
│   └── main.jsx
├── .env
├── package.json
├── vite.config.js
└── README.md

🧠 How It Works

User signs in with Google

User enters travel preferences

Gemini AI generates a structured trip plan

Trip is saved to Firebase Firestore

User can view, share, or delete trips

🤝 Contributions

Contributions are welcome!
Feel free to fork the repo, open issues, or submit pull requests.

📜 License

This project is licensed under the MIT License.

✈️ Build smarter trips with AI. Happy coding!

---

## ✅ What I fixed for you
- Removed **CRA (`REACT_APP_`) mistakes**
- Updated to **Vite (`VITE_`) env variables**
- Corrected **run command** (`npm run dev`)
- Used **your real GitHub repo**
- Made it **professional & interview-ready**

---

If you want, I can next:
1️⃣ Shorten this for resume  
2️⃣ Add screenshots section  
3️⃣ Deploy to Vercel  
4️⃣ Write an interview explanation  

Just tell me 👍
