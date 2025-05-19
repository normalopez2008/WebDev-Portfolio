# WebDev-Portfolio

This is a full-stack app that explains my career goals, contains some information I learned in Web Development class and also has a travel log where I am able to record, view, and manage travel experiences using a simple and elegant interface. It is built with **React** on the frontend and **Node.js + Express + MongoDB** on the backend.

---

## 🚀 Features

- 📍 Add a new travel location with age and date
- 🗂️ View a list of all recorded travels
- ✏️ Edit existing travel entries
- ❌ Delete travels from the database
- 📡 Frontend-backend integration with API routing
- 🛠️ Uses MongoDB Atlas for remote cloud data storage

---

## 🧱 Tech Stack

| Layer     | Technology         |
|-----------|--------------------|
| Frontend  | React, JavaScript  |
| Backend   | Node.js, Express   |
| Database  | MongoDB Atlas      |
| Dev Tools | Nodemon, dotenv    |

---

## 📂 Project Structure

```
portfolio-2/
├── backend/
│   ├── travels-controller.mjs
│   ├── travels-model.mjs
│   ├── .env
│   └── package.json
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.js
│   ├── public/
│   └── package.json
```

---

## 🛠️ Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/normalopez2008/WebDev-Portfolio.git
cd WebDev-Portfolio
```

### 2. Configure Environment Variables

In the `backend/.env` file, add your MongoDB connection string:

```
**Example ->** MONGODB_CONNECT_STRING=mongodb+srv://<username>:<password>@cluster0.mongodb.net/travelsDB?retryWrites=true&w=majority
PORT=3000
```

> Ensure your MongoDB Atlas user has access and IP is whitelisted.

### 3. Install dependencies 

#### Backend:
```bash
cd backend
npm install
```

#### Frontend (in another terminal):
```bash
cd frontend
npm install
```

---

### 4. Run the App

#### Start Backend (from respective terminal):

```bash
npm start
```

#### Start Frontend (from respective terminal):

```bash
npm start
```

App will be running on:  
- Frontend: [http://localhost:8000](http://localhost:8000)  
- Backend: [http://localhost:3000](http://localhost:3000)

---

## 🧪 Test Data Format

When adding a travel entry, the app expects:

```json
{
  "location": "Paris",
  "age": 25,
  "date": "2023-12-15"
}
```

---

## 📸 Screenshots

**Home Page**
<img width="1270" alt="Screenshot 2025-05-18 at 10 06 04 PM" src="https://github.com/user-attachments/assets/87c63d0e-b2c6-4b91-8e06-9e66df9229f4" />

**Travel Log Page**
<img width="1219" alt="Screenshot 2025-05-18 at 10 05 45 PM" src="https://github.com/user-attachments/assets/4f8db361-9e92-421e-985f-d1ba0c9e11c1" />

**Topics Page**
<img width="1270" alt="Screenshot 2025-05-18 at 10 06 25 PM" src="https://github.com/user-attachments/assets/3f87b5e4-de67-45ab-8a6f-336635033698" />


---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss.

---

## 🙌 Acknowledgments

- Thanks to MongoDB Atlas for cloud hosting
- Created as part of Oregon State Web Development Course: Full Stack Portfolio assignment
