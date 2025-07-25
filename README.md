# 📁 DocStacker - Document Management System

**DocStacker** is a full-stack Document Management System (DMS) that allows users to securely store, manage, and organize their documents. The application features a responsive UI with user authentication, profile management, and document-related operations.

---

## 🚀 Features

### 🔐 User Authentication
- User registration with email and password
- Secure login using JSON Web Tokens (JWT)
- Password hashing with `bcryptjs`
- Protected API routes

### 🖥️ User Interface
- Modern, clean dashboard layout
- Dark/light mode toggle
- Fully responsive (mobile/tablet/desktop)
- Animated UI using Animate.css
- Profile management with avatar support

### 📂 Document Management
- File upload functionality
- Document organization dashboard
- File preview and sharing UI (interface-ready)
- Contact and feedback forms

### 🛠️ Additional Features
- Feedback submission system
- Notification-ready UI
- Contact form integration

---

## 🧰 Tech Stack

### Frontend
- HTML5, CSS3, JavaScript (Vanilla)
- Custom CSS with modular organization
- Font Awesome for icons
- Animate.css for UI animations

### Backend
- Node.js with Express.js
- MongoDB with Mongoose
- JWT for authentication
- bcryptjs for password encryption
- dotenv for environment configuration

---

## 📁 Project Structure
### Frontend
 / (Root)
┣ 📂 CSS/
┣ 📂 JS/
┣ 📄 index.html
┣ 📄 LogIn.html
┣ 📄 SignUp.html
┣ 📄 UserDashboard.html
┣ 📄 Contactus.html
┣ 📄 FeedBack.html
┣ 📄 My_document.html
┗ 📄 Upload.html

### Backend
📦 / (Root)
┣ 📂 models/
┃ ┗ 📄 User.js
┣ 📂 routes/
┃ ┗ 📄 auth.js
┣ 📄 server.js
┣ 📄 .env
┗ 📄 package.json

Contributions are welcome!
Feel free to fork this repo and submit pull requests.

