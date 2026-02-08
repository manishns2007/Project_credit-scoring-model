# 🏠 DormFix – Hostel Management System

DormFix is a **modern hostel management system** built using **Next.js** and **Firebase Studio**, designed to simplify hostel operations such as complaints, maintenance, room management, and communication between students and administrators.

This project serves as a scalable foundation for building a real-world, production-ready hostel or dormitory management platform.

---

## 🚀 What is DormFix?

DormFix helps hostels and dormitories manage day-to-day issues efficiently by providing:

* 🧾 Complaint & issue reporting (electricity, water, cleanliness, etc.)
* 🛠️ Maintenance tracking and status updates
* 👨‍🎓 Student-friendly interface
* 🧑‍💼 Admin dashboard for wardens & staff
* 🔔 Real-time updates using Firebase
* 🔐 Secure authentication & role-based access

---

## 🧱 Project Architecture

DormFix follows a **modular and scalable architecture**, separating student-facing features, admin controls, backend logic, and documentation. This makes the system easy to maintain and extend.

```
DormFix/
│
├── Student_App/
│   ├── issue_report/      # Students report hostel issues
│   ├── uploads/           # Images/files uploaded with complaints
│   └── notifications/     # Status updates & alerts for students
│
├── Admin_Dashboard/
│   ├── issue_tracker/     # View & manage reported issues
│   ├── analytics/         # Hostel issue insights & reports
│   └── staff_assignment/  # Assign staff to resolve issues
│
├── Backend/
│   ├── auth/              # Authentication & authorization logic
│   ├── issues/            # Issue CRUD operations
│   └── users/             # Student, admin, and staff management
│
├── Database/
│   └── (Firestore / DB schemas & rules)
│
├── Docs/                  # Project documentation & diagrams
├── LICENSE
└── README.md
```

### 🔹 Architectural Overview

* **Student_App**: Handles all student interactions such as reporting issues and receiving notifications
* **Admin_Dashboard**: Provides wardens/admins with tools to track, analyze, and assign issues
* **Backend**: Core business logic, APIs, and security rules
* **Database**: Stores complaints, users, statuses, and logs securely

This structure supports **role-based access**, clean separation of concerns, and future scalability.

---

## 🛠️ Tech Stack

* **Frontend**: Next.js (App Router)
* **Backend**: Firebase (Firestore, Auth)
* **Language**: TypeScript
* **Styling**: CSS / Tailwind (optional)
* **Hosting**: Firebase Hosting / Vercel

---

## ⚙️ Prerequisites

Make sure you have the following installed:

* Node.js **18+**
* npm or yarn
* Firebase CLI

Check versions:

```bash
node -v
npm -v
firebase --version
```

---

## 📥 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/dormfix.git
cd dormfix
```

---

### 2️⃣ Install Dependencies

```bash
npm install
```

or

```bash
yarn install
```

---

### 3️⃣ Configure Firebase

1. Go to **Firebase Console**
2. Create a new project
3. Enable:

   * Authentication (Email/Password)
   * Firestore Database
4. Copy Firebase config and add it inside:

```
src/lib/firebase.ts
```

---

### 4️⃣ Run the Project Locally

```bash
npm run dev
```

Open your browser at:

```
http://localhost:3000
```

🎉 DormFix is now running locally!

---

## 🧭 How to Use DormFix

### 👨‍🎓 Student Flow

* Login / Register
* Submit hostel-related complaints
* Track complaint status
* Receive updates once resolved

### 🧑‍💼 Admin / Warden Flow

* View all complaints
* Assign maintenance staff
* Update issue status (Pending / In Progress / Resolved)
* Monitor hostel operations

---

## 🧩 Key Features (Planned & Implemented)

* ✅ Firebase Authentication
* ✅ Complaint Management System
* ⏳ Role-based dashboards (Admin / Student)
* ⏳ Push notifications
* ⏳ Analytics & reports

---

## 🔐 Security & Best Practices

* Role-based access using Firebase rules
* Secure Firestore queries
* No sensitive keys committed to repo

---

## 📈 Future Enhancements

* Room allocation system
* Fee & payment tracking
* Attendance & entry logs
* Mobile app (React Native)
* Dark mode UI

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🧑‍💻 Author

**Manish**
B.Tech IT | Full Stack & System Design Enthusiast

If you like this project, don’t forget to ⭐ the repo!

