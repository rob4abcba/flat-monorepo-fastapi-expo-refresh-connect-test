# fullstack_app13

A minimal fullstack Expo + FastAPI app scaffolded by `scaffold_fullstack_app13.py`.

## 🧱 Stack

- 📱 **Frontend**: React Native + Expo (`frontend-expo`)
- ⚙️ **Backend**: FastAPI (`backend-fastapi`)
- 📦 **Shared Types**: `common/`

---

## 🚀 Quickstart

### 1. Backend

```bash
cd backend-fastapi
uvicorn main:app --reload
```

The FastAPI server will be available at:  
👉 http://localhost:8000

### 2. Frontend (Expo)

```bash
cd frontend-expo
npx expo start
```

Open the Expo app in your mobile emulator or device.  
Make sure the backend is running before starting the app so the refresh tab works.

---

## ✅ Features

- `/ping` FastAPI backend route
- Working frontend **Refresh** tab:
  - Calls backend endpoint and displays response
- Hot-updatable backend message

---

## 📌 Project Structure

```
fullstack_app13/
├── backend-fastapi/       # FastAPI backend server
│   └── main.py            # Core app
├── frontend-expo/         # Expo React Native frontend
│   └── app/               # Screens, tabs, components
├── common/                # Shared constants or types
├── scaffold_fullstack_app13.py
└── README.md              # This file
```

---

## 🛠️ To Do

- [ ] Add more backend endpoints (e.g., `/status`, `/echo`, etc.)
- [ ] Add persistent backend storage (e.g., SQLite, Postgres)
- [ ] Build out additional UI tabs or screens
- [ ] Auth integration (optional)
- [ ] Testing + CI setup

---

## 🧪 Git Setup

If not already initialized:

```bash
cd fullstack_app13
git init
git add .
git commit -m "Initial commit: Working fullstack Expo + FastAPI app"
```

Then push to your GitHub repo:

```bash
git remote add origin https://github.com/YOUR_USERNAME/fullstack_app13.git
git push -u origin main
```

---

## 🪪 License

[MIT](LICENSE)
