# 📚 LearnCircle - Learning Management System (LMS)

🔗 **Live Demo:** [LearnCircle](https://learn-circle-lms-frontend.vercel.app/)


## **Overview**  
LearnCircle is a **full-featured Learning Management System (LMS)** built with the **MERN stack**. It enables learners to enroll in courses, educators to manage their content, and provides a secure payment system with **Stripe**. Also User can track progress of the enrolled courses. 

---

## 🚀 Features
- 🔐 **Authentication & Authorization** using [Clerk](https://clerk.dev/)  
- 📚 **Course Management** – Add, update and delete courses (Educator Dashboard)  
- 🎥 **Video Lectures** – Embedded YouTube videos for course content  
- ✍️ **Rich Course Description** with [Quill Editor](https://quilljs.com/)  
- 💳 **Secure Payments** via [Stripe](https://stripe.com/)  
- 📊 **Educator Dashboard** to manage courses, total earnings and track student enrollments  
- 👨‍🎓 **Student Dashboard** to view purchased courses and progress  
- 🌐 **Responsive UI** – Works seamlessly on desktop and mobile  

---

## 🛠️ Tech Stack
**Frontend:**
- React.js
- Context API (for state management)
- React Router
- Tailwind CSS
- Clerk Authentication
- React Quill (Rich Text Editor)

**Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose ODM)
- Stripe Payment Gateway
- Clerk for User management

**Other Integrations:**
- YouTube (for video content)
- Vercel (Frontend Hosting)

---

## 📂 Project Structure
```bash
LearnCircle/
├── frontend/        # Frontend (React)
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   └── assets/
│   └── package.json
├── backend/        # Backend (Node.js + Express)
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   ├── config/
│   └── package.json
└── README.md
```

---

## **Installation**  
### **1. Clone the repository**  
```bash
git https://github.com/krishna-bata/learn-circle-lms.git
cd learncircle
```

### **2. Install dependencies**  
#### **Frontend**  
```bash
cd frontend
npm install
```

#### **Backend**  
```bash
cd backend
npm install
```

### **3. Configure Environment Variables**  
Create a `.env` file in the **backend** directory and add:  
```env
PORT=your_server_port
CURRENCY = "your_currency"
MONGODB_URI= "your_mongodb_connection_string"
CLERK_WEBHOOK_SECRET = "your_clerk_webhook_secret"
CLERK_PUBLISHABLE_KEY= "your_clerk_publishable_key"
CLERK_SECRET_KEY= "your_clerk_secret_key"
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_secret_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
STRIPE_PUBLISHABLE_KEY = "your_stripe_publishable_key"
STRIPE_SECRET_KEY = "your_stripe_secret_key"
STRIPE_WEBHOOK_SECRET = "your_stripe_webhook_secret"

```

Create a `.env` file in the **frontend** directory and add:  
```env
VITE_BACKEND_URL=your_backend_url
VITE_CLERK_PUBLISHABLE_KEY= "your_vite_clerk_publishable_key"
VITE_CURRENCY= "your_currency"
```

### **4. Start the Application**  
#### **Backend**  
```bash
cd backend
npm run server
```
#### **Frontend**  
```bash
cd frontend
npm run dev
```

---

## 🚀 Acknowledgements
- [Clerk](https://clerk.dev/) for Authentication  
- [Quill Editor](https://quilljs.com/) for Rich Text Editor
- [Stripe](https://stripe.com/) for Payment Gateway  
- [MongoDB](https://www.mongodb.com/) for Database  
- [Vercel](https://vercel.com/) for Hosting  
- [Youtube](https://www.youtube.com/) for Course Content 

---

## **Upcoming Features**  
🚀 **Certificates of Completion** - Generate downloadable PDF certificates when a student completes a course.  
🚀 **Admin Dashboard (Super Admin)** - Manage users (students + educators), courses, and payments.

---

## **Contributing**  
Contributions are welcome! Feel free to fork the repo, create a new branch, and submit a pull request.

---
