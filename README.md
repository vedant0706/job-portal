# 💼 Job Portal – Production-Grade Full Stack Recruitment Platform

![Stars](https://img.shields.io/github/stars/vedant0706/job-portal?style=for-the-badge)
![Forks](https://img.shields.io/github/forks/vedant0706/job-portal?style=for-the-badge)
![Watchers](https://img.shields.io/github/watchers/vedant0706/job-portal?style=for-the-badge)
![Issues](https://img.shields.io/github/issues/vedant0706/job-portal?style=for-the-badge)

---

Job Portal is a **production-grade, full-stack recruitment platform** engineered to demonstrate real-world software engineering practices. The project showcases secure authentication, scalable backend architecture, clean frontend design, and recruiter-level business logic.

Built using the MERN stack, Job Portal follows industry-standard patterns used in hiring platforms.

---

## 📌 Table of Contents

- 🌟 Features  
- 🛠 Tech Stack  
- 🚀 Getting Started  
- 📁 Project Structure  
- 🎯 Usage  
- 🔒 Security Features  
- 🌐 Deployment  
- 🤝 Contributing  
- 🖼 Screenshots  
- 👨‍💻 Author  
- 🙏 Acknowledgments  
- 📞 Support  

---

## 🌟 Key Highlights

### 👤 Applicant Capabilities
- Secure authentication (Email & Google login via Clerk)
- Browse job listings
- Apply for jobs
- Track application status (Accepted / Rejected / Pending)
- View application history
- Responsive user experience

### 🏢 Recruiter & Business Logic
- Recruiter authentication using company email
- Post and manage job listings
- View job applications
- Update application status:
  - Accept  
  - Reject  
  - Pending  
- Company-based job management

### 🎨 UI / UX Engineering
- Clean, minimal UI design  
- Fully responsive layout  
- TailwindCSS styling  
- Toast notifications  
- Smooth navigation  

---

## 🛠 Technology Stack & Engineering Choices

### 🎨 Frontend
- React.js  
- Vite  
- Tailwind CSS  
- Axios  
- React Router DOM  
- Context API  
- React Toastify  

### ⚙ Backend
- Node.js  
- Express.js  
- MongoDB (Mongoose)  
- Clerk Authentication  
- JWT  
- bcrypt  
- CORS  

---

## 🚀 Getting Started (Local Development)

### ✅ Prerequisites
- Node.js (v14+)  
- MongoDB Atlas  
- Clerk account credentials  

---

## 📥 Installation

### 🔹 Clone the repository
```
git clone https://github.com/vedant0706/job-portal.git

cd job-portal
```
---

### ⚙️ Environment Variables
Create a .env file in the server folder:
```
MONGO_URI=your_mongodb_connection_string
CLERK_SECRET_KEY=your_clerk_secret_key
CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
JWT_SECRET=your_jwt_secret
```
---

### ▶️ Run the Application

🚀 Backend: 
```
npm run server
```
🌐 Frontend:
```
npm run dev
```

---

### 📁 Project Architecture
```
JOB_PORTAL/
├── client/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   └── App.jsx
│   └── package.json
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
│
└── README.md
```
---

### 🎯 Application Workflows
👤 Applicants
- Register / Login with Clerk
- Browse job listings
- Apply for jobs
- Track application status

🏢 Recruiters
- Login using company email
- Post new jobs
- Manage job applications
- Update applicant status

--

### 🔒 Security & Best Practices
- Clerk authentication (Google + Email)
- JWT-based session handling
- HTTP-only cookies
- Password encryption
- Role-based route protection
- Secure CORS configuration

---

### 🌐 Deployment & Production Readiness
- Frontend: Vercel
- Backend: Vercel
- Database: MongoDB Atlas
- Deploy frontend:

```
vercel deploy --prod
```
--

### 🤝 Contribution Guidelines
Contributions are welcome 💙

```
git checkout -b feature/YourFeatureName
git commit -m "Add: YourFeatureName"
git push origin feature/YourFeatureName
Open a Pull Request 🚀
```
---

### 🖼️ Application Screenshots

📸 Login Page:
![Login Page](/client/src/assets/loginPage.png)

📸 Applied Job Page:
![Applied Job Page](/client/src/assets/appliedJobsPage.png)

📸 Apply Job Page:
![Apply Job Page](/client/src/assets/applyJobPage.png)

📸 Add Job Page:
![Add Job Page](/client/src/assets/addJobpage.png)

📸 Manage Job Page:
![Manage Job Page](/client/src/assets/manageJobPage.png)

📸 View Applications Page:
![View Applications Page](/client/src/assets/viewApplicationsPage.png)


---

### 👨‍💻 About the Developer
***Vedant Jadhav***
- 💡 Full Stack Developer | MERN Stack Enthusiast
- 🐙 GitHub: https://github.com/vedant0706
- 💼 LinkedIn: https://www.linkedin.com/in/vedant-jadhav-0b1947340
- 🌐 Portfolio: https://jadhavvedant.vercel.app

---

### 🙏 Acknowledgments & References
Special thanks to:

- ⚛ React Community
- 🍃 MongoDB Documentation
- 🔐 Clerk Authentication
- 🎨 TailwindCSS
- 🌍 Open-source Contributors
- 📞 Contact & Support

If you need help or want to collaborate:
#### 📧 Email: vedantjadhav173@gmail.com

#### 🐞 GitHub Issues: Open an issue in this repository
---

### 🌐 Live Demo (Production)
#### 🚀 Live Project:
🔗 https://job-portal-client-eight-sigma.vercel.app


<div align="center">
**Built to demonstrate real-world full-stack engineering skills** <br />
**Made with ❤️ by Vedant Jadhav**
</div>