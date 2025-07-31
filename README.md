# 🏥 Medicare Frontend

Welcome to **Medicare Frontend**! 🚀 This is a modern web application designed to help patients access world-class healthcare services. This project is the frontend for the Medicare platform, built with React, Vite, and Tailwind CSS, and connects to a dedicated backend ([Medicare Backend](https://github.com/Jasharaj/Medicare-Backend)).

## 🌐 Live Demo

Check out the live site: [Medicare Frontend on Vercel](https://medicare-frontend-two.vercel.app) 👀

---

## ✨ Features

- 🩺 **Healthcare Services**: Browse and request appointments for Cancer Care, Labor & Delivery, Heart & Vascular, Mental Health, and more.
- 🎨 **Modern UI**: Responsive design using Tailwind CSS and custom components.
- 🔒 **Authentication**: Patient and doctor registration/login with profile photo upload (Cloudinary integration planned).
- 🏆 **Informational Pages**: Learn about the hospital, its accolades, and medical staff.
- 👤 **User Roles**: Supports multiple roles (patient, doctor) with differentiated signup and dashboard.
- 🛎️ **Toast Notifications**: Real-time feedback for actions (success/error messages).
- 🧭 **Routing**: Page navigation handled with React Router.

---

## 🧰 Technologies Used

- ⚛️ **React**: Frontend library for building user interfaces.
- ⚡ **Vite**: Fast build tool for React.
- 💨 **Tailwind CSS**: Utility-first CSS framework.
- 🍞 **React Toastify**: Notification system.
- 🌥️ **Cloudinary** (planned): Image upload and hosting.
- 🟨 **JavaScript**: Main programming language.

---

## 🏁 Getting Started

### Prerequisites

- 🟩 Node.js (v16+ recommended)
- 📦 npm or yarn

### Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Jasharaj/Medicare-Frontend.git
   cd Medicare-Frontend
   ```

2. **Install dependencies**  
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Configure Backend API**  
   - The app is pre-configured to use [Medicare Backend](https://medicare-backend-6zdm.onrender.com/api/v1).
   - If running locally, update `src/config.js`:
     ```js
     export const BASE_URL = "http://localhost:5000/api/v1";
     ```

4. **Run the development server**  
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. **Open in browser**  
   ```
   http://localhost:5173
   ```

---

## 📂 Project Structure

```
├── src/
│   ├── assets/        # Images, icons, data
│   ├── components/    # Reusable UI components
│   ├── context/       # React Context (Auth)
│   ├── layout/        # Page layout components
│   ├── pages/         # Application pages (Home, Signup, etc.)
│   ├── routes/        # Page routing
│   ├── index.css      # Global styles
│   ├── config.js      # API base URL and token handling
│   └── main.jsx       # App entry point
├── index.html
├── tailwind.config.js
├── postcss.config.js
└── package.json
```

---

## 📝 Usage

- ✍️ **Sign Up**: Register as a patient or doctor, upload a profile photo.
- 🔍 **Browse Services**: View medical specialties and hospital information.
- 📅 **Request Appointments**: Use the UI to book appointments.
- 📱 **Responsive Design**: Works across desktop and mobile devices.

---

## 🤝 Contributing

Pull requests are welcome! 🎉 Feel free to open issues for suggestions, bug reports, or feature requests.

---

## 📜 License

This project does not currently specify a license.

---

## 🔗 Related Projects

- [Medicare Backend](https://github.com/Jasharaj/Medicare-Backend) – Node.js API powering the platform.

---

## 👨‍💻 Author

[Jasharaj](https://github.com/Jasharaj) 🙌
