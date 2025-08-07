# ConsentLens – AI-Powered Image Consent Checker 🔒

A web-based platform that empowers users to verify whether they’ve given consent for images containing them to be used or shared online. ConsentLens promotes ethical image usage through facial recognition and decentralized consent tracking.

---

## 📁 File Structure

ConsentLens/
│
├── client/ # Frontend (React.js)
│ ├── public/
│ └── src/
│ ├── components/ # Reusable UI components
│ ├── pages/ # App pages like Home, Dashboard
│ ├── services/ # API calls
│ ├── App.js # Main component
│ └── index.js # Entry point
│
├── server/ # Backend (Node.js + Express)
│ ├── controllers/ # Request logic
│ ├── routes/ # API routes
│ ├── models/ # Mongoose Schemas
│ ├── utils/ # Utility functions (face recognition etc.)
│ ├── uploads/ # Uploaded images
│ ├── config/ # DB, environment config
│ ├── app.js # Main Express app
│ └── server.js # Server setup
│
├── .gitignore
└── README.md

---

## 🛠 Tech Stack

| Area       | Tech Used                          |
|------------|------------------------------------|
| Frontend   | React.js, Tailwind CSS             |
| Backend    | Node.js, Express.js                |
| Database   | MongoDB                            |
| Auth       | JWT, OAuth (optional)              |
| AI/ML      | face-api.js (Browser-based) OR Python (FaceNet / DeepFace) |
| Storage    | Local / Cloud (Cloudinary, Firebase) |
| Consent DB | JSON-LD or Smart Contracts (optional) |

---

## 🚀 Getting Started

### Prerequisites

- Node.js & npm
- MongoDB local or Atlas
- Git


