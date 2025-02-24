# Jobby App

## 📖 Project Overview
The **Jobby App** is a job search platform built using the **MERN Stack** that allows users to search for job listings based on filters and categories. It features user authentication, protected routes, and responsive design, ensuring a smooth user experience across devices.

---

## 🚀 Features

- **User Authentication:** Secure login and logout using **JWT tokens**.
- **Dynamic Job Search:** Filter jobs based on title, location, and employment type.
- **Protected Routes:** Restrict access to job listings and profiles for unauthenticated users.
- **Real-Time API Integration:** Display **100+ job listings** using Fetch API.
- **Responsive Design:** Optimized for mobile, tablet, and desktop screens.
- **Error Handling:** User-friendly alerts for API failures and invalid credentials.

---

## 🛠️ Technologies Used

### **Frontend:**
- React.js
- HTML5, CSS3, Bootstrap
- JavaScript (ES6+)
- React Router

### **Backend:**
- Node.js
- Express.js
- JWT Authentication

### **Database:**
- MongoDB

### **Other Tools:**
- Git & GitHub
- VS Code
- Fetch API

---

## 📸 Screenshots

1. **Login Page:** User login with JWT-based authentication.
2. **Job Listings:** Filterable job search results.
3. **Job Details:** Detailed view of each job listing.
4. **Error Handling:** Proper alerts for invalid credentials or API failures.

---

## 🔧 Installation & Setup

1. **Clone the Repository:**
```bash
git clone https://github.com/yourusername/jobby-app.git
cd jobby-app
```

2. **Install Dependencies:**
```bash
npm install
```

3. **Run the Application:**
```bash
npm start
```

4. **Access the App:**
Visit `http://localhost:3000` in your browser.

---

## 📚 API Endpoints

- **Login:** `POST /login`
- **Job Listings:** `GET /jobs`
- **Job Details:** `GET /jobs/:id`

---

## ✅ Environment Variables
Create a `.env` file in the root directory and add the following variables:
```env
REACT_APP_API_URL=http://localhost:4000
JWT_SECRET=your_secret_key
```

---

## 🚀 Deployment
To deploy the app to production:
1. Build the app:
```bash
npm run build
```
2. Deploy using a platform like Netlify, Vercel, or GitHub Pages.

---

## 📝 License
This project is licensed under the **MIT License**. Feel free to use and modify it as per your needs.

---

## 🤝 Contributing
Contributions are welcome! If you'd like to improve the app, please follow these steps:
1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

---

## 📞 Contact
For any queries or suggestions:
- **Email:** chmaneshkumar2002@gmail.com
- **LinkedIn:** [Insert Link Here]

