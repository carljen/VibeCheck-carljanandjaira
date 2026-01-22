# VibeCheck API + Button Smash UI

A simple Node.js API and HTML frontend built for CPE 411L Activity #3.

## 🛠️ How to Run

### 1. Setup Backend
Open a terminal in the `backend` folder and run the following commands to install dependencies and start the server:

```bash
cd backend
npm install
node index.js
```
*You should see the message: `VibeCheck API running at http://localhost:3000`*

### 2. Setup Frontend
1. Navigate to the `frontend` folder.
2. Open the `index.html` file in your web browser (Chrome, Edge, etc.).

---

## 🔌 API Endpoints

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| `GET` | `/api/fortune` | Returns a random fortune cookie message. |
| `GET` | `/api/joke` | Returns a random developer joke. |
| `GET` | `/api/vibe?mood=x` | Returns a vibe based on mood (happy, tired, stressed). |
| `POST` | `/api/smash` | Increases the global smash counter. |
| `GET` | `/api/smashes` | Returns the current smash count. |
| `GET` | `/api/secret?code=411L` | Unlocks a secret message if the code is correct. |

---

## 👥 Contributors
* **Student A** (Backend Lead)
* **Student B** (Frontend Lead)