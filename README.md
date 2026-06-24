# 🥗 CalTrack

**MealTrace Nutrition Tracker** — a calorie and macro tracking app with AI-powered meal photo analysis.

CalTrack is a variant of MealTrace featuring a lightweight Node.js API server alongside the static frontend. It analyzes meal photos to log calories, protein, carbs, fat, and fiber.

---

## ✨ Features

- 📸 **AI Meal Analysis** — Upload meal photos for automatic nutritional breakdown
- 🔐 **User Authentication** — Secure sign-in via Supabase Auth
- 📊 **Nutrition Charts** — Visualize intake with Chart.js
- 🖥️ **Node.js Server** — Lightweight API server (`server.js`) for backend operations
- 📅 **Meal History** — Review and track daily/weekly nutrition
- 🎯 **Goal Setting** — Custom calorie and macro targets

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Vanilla HTML/CSS/JS, Inter font |
| Backend | Node.js (server.js) |
| Charts | Chart.js 4 |
| Auth & Database | Supabase (PostgreSQL) |
| Deployment | GitHub Pages |

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/rishitmanktala/CalTrack.git
   cd CalTrack
   ```

2. **Configure environment:**
   ```bash
   cp .env.example .env
   ```
   Update with your Supabase credentials.

3. **Start the server:**
   ```bash
   npm start
   ```

4. Open `http://localhost:3000` in your browser.

---

## 📄 License

This project is open source.
