# fullstack_app13

A minimal fullstack Expo + FastAPI app scaffolded by `scaffold_fullstack_app13.py`.

## Stack

- 📱 Frontend: React Native + Expo (`frontend-expo`)
- ⚙️ Backend: FastAPI (`backend-fastapi`)
- 🧱 Shared Types: `common/`

## How to Run

### Backend

```bash
cd backend-fastapi
uvicorn main:app --reload
```

### Frontend

```bash
cd frontend-expo
npx expo start
```

Ensure the backend is running at http://localhost:8000 before launching the Expo app.

Features
✅ Working /ping backend endpoint

✅ Refresh screen tab that reads backend response

🔄 Can hot-update response content and see it reflected in app


To Do
 Add more endpoints

 Add persistent backend storage

 Build out UI tabs

 License
MIT



---

## ✅ 4. Initialize Git at the root

If not already:

```bash
cd fullstack_app13
git init
git add .
git commit -m "Initial commit: Working fullstack Expo + FastAPI app"
```

