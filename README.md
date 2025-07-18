# 🧑‍🎓 UFree (Legacy) – Freelance Job Portal for Students

UFree is a full-stack web application initially built as part of my final-year university project. The platform was created to connect university students with freelance and part-time job opportunities, helping them gain real-world experience while studying.

⚠️ **Note**: This version is the **original build** developed during my academic program and is no longer actively maintained. A complete redesign and upgrade of UFree is underway [see new repo link when available].

---

## ✨ Core Features

- User Registration & Login (Student and Employer roles)
- Job Posting and Job Search Interface
- Employer Dashboard to Manage Listings
- Student Dashboard to Track Applications
- CV Upload & Application Form
- Simple Admin Panel (planned but not fully implemented)

---

## 🛠️ Tech Stack

- **Frontend**: React.js, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (with Mongoose)
- **Authentication**: JWT
- **State Management**: React Context API
- **Miscellaneous**: Multer for CV Upload, Nodemailer for email (planned)

---

## 📁 Project Structure (Simplified)
ufree/

- ├── client/ # Frontend (React)
- └── server/ # Backend (Node/Express)


---

## ⚙️ Setup Instructions (Local Dev)

```bash
# Clone this repository
git clone https://github.com/Lhartey/ufree.git
cd ufree

# Start backend server
cd server
npm install
npm start

# Start frontend server
cd ../client
npm install
npm start
