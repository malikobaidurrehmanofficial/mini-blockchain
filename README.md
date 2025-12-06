# 🔗 Mini Blockchain System — FastAPI + Interactive Web Visualizer

A fully working **educational blockchain simulation** developed by the **Underground Unit**.  
This project demonstrates core Information Security concepts including hashing, proof-of-work, immutability, tamper detection, distributed nodes, and 51% attacks — all with a beautiful interactive frontend.

Developed as part of the **Information Security Lab Project (Fall 2025)**.

---

## 📁 Project Structure

my-blockchain-project/
│
├── backend/ # Python FastAPI backend
│ ├── app.py # API routes for blockchain operations
│ ├── blockchain_core.py # Full blockchain engine
│ ├── init.py # Makes the folder a Python module
│ ├── requirements.txt # Backend dependencies
│
├── frontend/ # Web UI (HTML + Tailwind + React)
│ ├── index.html # Homepage + blockchain visualizer
│ ├── about.html # About page with team section
│ ├── visualizer.html # Optional secondary UI
│ ├── hassan.png # Team images
│ ├── irfan.png
│ ├── mubashir.png
│ ├── obaid.png
│ ├── underground.png
│
└── README.md # Project documentation
## 🚀 Features Overview

### 🔥 **Blockchain Engine (Python)**  
- Block structure (index, timestamp, data, hash, previous hash, nonce)  
- Proof-of-Work implementation with configurable difficulty  
- Mining reward system (balances stored for each miner)  
- Data block creation & reward block creation  
- Chain validation + tamper detection  
- 51% attack simulation (re-mines from tampered block)  
- Multi-node simulation with **Longest Chain Rule**  

### 🎨 **Frontend Interface (HTML + React + Tailwind)**  
- Interactive blockchain visualizer  
- Mine reward blocks  
- Add custom data blocks  
- Tamper with blocks & instantly check chain validity  
- Simulate 51% attack visually  
- View miner balances in real-time  
- Node creation, mining on nodes, and node synchronization  
- Professional UI with animations, cards, and dark theme  

---

## 🧪 Running Locally

### **1️⃣ Backend – FastAPI**

Open terminal:

cd backend
pip install -r requirements.txt
python -m uvicorn app:app --reload

yaml
Copy code

Backend URL:

http://127.0.0.1:8000

yaml
Copy code

API Documentation:

http://127.0.0.1:8000/docs

yaml
Copy code

---

### **2️⃣ Frontend – Local Browser**

Open:

frontend/index.html

csharp
Copy code

If using a deployed backend, update the frontend API base:

```js
const API_BASE = "https://your-backend.onrender.com";
🌍 Deployment Guide
⭐ Backend Deployment (Render – Free)
Push your project to GitHub

On Render → “New Web Service”

Select your repo

Set Root Directory to:

nginx
Copy code
backend
Set Build Command:

nginx
Copy code
pip install -r requirements.txt
Set Start Command:

nginx
Copy code
uvicorn app:app --host 0.0.0.0 --port 10000
Render will give you a live backend URL:

arduino
Copy code
https://your-backend.onrender.com
⭐ Frontend Deployment (GitHub Pages – Free)
Go to GitHub → Repository Settings

Open Pages

Set:

makefile
Copy code
Branch: main
Folder: /frontend
Your frontend will be live at:

perl
Copy code
https://yourusername.github.io/my-blockchain-project/
Now your frontend communicates with the backend perfectly.

👥 Team — Underground Unit
🚀 Project Developers
Malik Obaid Ur Rehman

Hassan Lodhi

Mubashir

Shahzaib

Irfanullah Khan

🧠 Instructor
Fatima Hameed, COMSATS University Abbottabad (Dhamtour Campus)

🎯 Purpose of the Project
This project was created as part of the Information Security Lab to help students understand:

Blockchain architecture

Block immutability

Hashing (SHA-256)

Mining rewards

Proof-of-Work consensus

Tampering & validation

Decentralization

Longest Chain Rule

51% attack simulation

The interactive UI makes it easier for students to visualize blockchain behavior in real time.

📝 License
This project is open-source and intended for educational purposes.

📬 Contact
For improvements or issues, please open a GitHub issue or contact the development team.

✨ Thank you for exploring our Mini Blockchain System! ✨

yaml
Copy code

---

If you'd like a version with:

✔ badges (Python, FastAPI, License, Stars)  
✔ screenshot previews  
✔ a GIF demo section  
✔ installation guide  
✔ contribution guidelines  

Just tell me **"upgrade README"**.






