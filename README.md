# SaaS-Subscription-Management-Platform-
A SaaS Subscription Management Platform built to manage subscription plans, customer accounts, billing details, renewals, and subscription status using a modern web application.
# SaaS Subscription Management Platform

## 📌 Project Overview
The SaaS Subscription Management Platform is a web-based application designed to simplify subscription management. It allows administrators to manage customers, subscription plans, billing details, and subscription renewals through a centralized dashboard.

## 🚀 Features
- User registration and login
- Secure user authentication
- Admin dashboard
- Create, update, and delete subscription plans
- Customer management
- Subscribe to available plans
- Track active and expired subscriptions
- Manage billing information
- Monitor subscription renewals
- Responsive user interface

## 🛠️ Technologies Used
- **Frontend:** React.js, HTML, CSS, JavaScript
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT
- **Version Control:** Git and GitHub

## 📂 Project Structure
```text
SaaS-Subscription-Management-Platform/
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
├── server/
│   ├── src/
│   ├── package.json
│   └── .env.example
├── README.md
└── .gitignore
```

## ⚙️ Installation and Setup

### 1. Clone the Repository
```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the Project Folder
```bash
cd SaaS-Subscription-Management-Platform
```

### 3. Install Dependencies
Install frontend and backend dependencies:

```bash
cd client
npm install
```

```bash
cd ../server
npm install
```

### 4. Configure Environment Variables
Create a `.env` file inside the server folder and configure:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 5. Run the Backend
```bash
cd server
npm run dev
```

### 6. Run the Frontend
Open another terminal:

```bash
cd client
npm run dev
```

Open the local URL displayed in the terminal in your browser.

## 💡 Project Purpose
This project aims to provide an easy and efficient solution for managing SaaS subscriptions, customer information, billing records, and renewal activities.

## 🔮 Future Enhancements
- Online payment gateway integration
- Automated email notifications
- Subscription analytics and reports
- Invoice generation
- Multiple subscription plans and pricing options

## 👨‍💻 Author
**Kunal Khadse**

## 📄 License
This project is developed for educational and internship purposes.
