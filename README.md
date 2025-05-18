# 💸 Payout Automation System

The **Payout Automation System** is a role-based web application designed to manage and streamline payment-related workflows for mentors and administrators. This system allows users to login as either an **Admin** or a **Mentor**, and dynamically displays relevant modules on the homepage based on their role.
collecting thire data .

---

## 🚀 Features

- 🎭 **Role-Based Login** (Admin or Mentor)
- 🧠 Intelligent Homepage: Shows modules based on selected role
- 📥 Upload session data
- 🧾 Generate and view receipts
- 💬 Integrated chat feature
- 📚 View audit logs
- 🧪 Test mode for dry-run operations
- 🔐 Secure logout (clears session data)
- ⚡ Responsive design for mobile and desktop

---

## 👤 User Roles & Access

| Role   | Accessible Modules |
|--------|---------------------|
| Admin  | Admin Dashboard, Upload Sessions, Generate Receipts, Receipt View, Chat, Audit Logs, Test Mode |
| Mentor | Mentor Dashboard, Mentor Sessions, Receipt View, Chat |

---

## 🧑‍💻 How to Use

### ✅ Step 1: Login

1. Open `login.html` in your browser.
2. Select a role (Admin or Mentor).
3. Enter email and password (dummy values are fine).
4. Click **Login**.

### ✅ Step 2: Homepage

- You'll be redirected to `index.html` (Home Page).
- Modules will be shown based on your selected role.

### ✅ Step 3: Navigation

Click on the cards to go to different pages such as:
- Admin Dashboard (`admin-dashboard.html`)
- Mentor Dashboard (`mentor-dashboard.html`)
- Chat (`chat.html`) and more.

### ✅ Step 4: Logout

- Click the **Logout** button to clear the session and return to login.

---

## 🗂️ File Structure

project-root/
│
├── index.html # Home Page (role-based module display)
├── login.html # Role-based login screen
├── admin-dashboard.html # Admin only
├── mentor-dashboard.html # Mentor only
├── session-upload.html # Admin only
├── generate-receipts.html # Admin only
├── receipt-view.html # Both roles
├── chat.html # Both roles
├── audit-log.html # Admin only
├── test-mode.html # Admin only
├── mentor-sessions.html # Mentor only
├── README.md # Project documentation



---

## ⚙️ Technologies Used

- HTML5
- CSS3 (Flexbox + Grid + Responsive Design)
- JavaScript (Vanilla)
- LocalStorage (for session role storage)

---

## 🧩 Local Setup Instructions

1. Clone or download the project folder.
2. Open `login.html` in any modern browser.
3. No backend setup is required.

---

## 🧠 Project Goals

- Simplify the process of managing payouts and mentoring sessions.
- Provide a clean and role-specific UI to avoid confusion.
- Make it easy for admins to handle financial records and communication.

---

## 🔐 Security Note

This project is frontend-only and uses `localStorage` to store user roles. For real-world use:
- Add authentication & session handling on the server
- Integrate with a secure backend (e.g., Node.js, Python Flask, etc.)

---

## 🌟 Future Enhancements

- 🔑 Real authentication system with user registration and encrypted sessions
- 🗃 Backend integration with a database
- 📈 Analytics dashboard
- 📩 Email notifications for sessions and receipts
- 🌍 Multi-language support

---

## 📅 License

This project is free to use for educational or demonstration purposes.

---

## 👨‍💻 Author

Made with ❤️ by [Sanu Bose]
> ⚠️ Note: This is a frontend-only project. On deployment, users must always login via `login.html` to properly set role in localStorage. Direct access to `index.html` will not work unless role is stored.
