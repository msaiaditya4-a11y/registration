# 🔐 Responsive Login & Registration UI

A modern, responsive, and interactive Login & Registration UI built using **HTML5, CSS3, Bootstrap 5, and JavaScript** as part of **Task 2** of the **Frontend Development Internship at ApexPlanet Software Pvt. Ltd.**

---

## 📸 Preview

![Project Preview](preview.png)

> Replace `preview.png` with a screenshot of your project.

---

## 🚀 Live Demo

🔗 Live Website: https://your-live-demo-link.com

---

## 📂 GitHub Repository

🔗 https://github.com/yourusername/login-registration-ui

---

## ✨ Features

- 🔐 Responsive Login Page
- 📝 Responsive Registration Page
- 📱 Mobile-First Design
- 🎨 Modern UI with Glassmorphism
- 🌈 Bootstrap 5 Components
- ✅ Form Validation
- 👁️ Show / Hide Password
- 🔒 Password Match Validation
- 📧 Email Validation
- ⚡ Smooth Hover Animations
- 🎭 Bootstrap Icons
- 🔤 Google Fonts (Poppins)
- 🌙 Clean & Professional Layout

---

## 🛠️ Built With

- HTML5
- CSS3
- Bootstrap 5
- JavaScript
- Bootstrap Icons
- Google Fonts

---

## 📁 Project Structure

```
Login-Registration-UI/
│
├── index.html
├── register.html
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
├── images/
│   ├── logo.png
│   └── preview.png
│
└── README.md
```

---

## 💻 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/login-registration-ui.git
```

Open the project

```bash
cd login-registration-ui
```

Run

Simply open `index.html` in your browser.

---

## 📷 Screenshots

### Login Page

![Login](images/login.png)

### Registration Page

![Register](images/register.png)

---

## 📚 What I Learned

- Bootstrap 5 Grid System
- Responsive Web Design
- Form Validation using JavaScript
- Password Visibility Toggle
- User-Friendly UI Design
- Bootstrap Components
- Mobile-First Development
- Modern CSS Styling

---

## 🎯 Internship Task

**Task 2 – Interactive UI & Frontend Development**

### Objective

Create a responsive Login & Registration UI using:

- HTML5
- CSS3
- Bootstrap 5
- JavaScript

---

## 🔮 Future Improvements

- Dark Mode
- Firebase Authentication
- Backend Integration
- Database Connectivity
- Remember Me Functionality
- Social Login
- Email Verification

---

## 🤝 Contributing

Contributions are welcome!

Feel free to fork the repository and submit a pull request.

---

## 📧 Contact

**M Leela Sai Aditya**

📩 Email: your-email@example.com

🔗 LinkedIn:
https://linkedin.com/in/your-linkedin

💻 GitHub:
https://github.com/yourusername

---

## ⭐ Support

If you like this project,

⭐ Star this repository

and share it with others.

---

## 📄 License

This project is licensed under the MIT License.

---

### Made with ❤️ by M Leela Sai Aditya

# Routes

TanStack Start uses **file-based routing**. Every `.tsx` file in this directory
defines a route. Do **not** create `src/pages/`, `src/routes/_app/index.tsx`, or
`app/layout.tsx` — those are Next.js / Remix conventions. The only root layout
is `src/routes/__root.tsx`.

## Conventions

| File | URL |
| --- | --- |
| `index.tsx` | `/` |
| `about.tsx` | `/about` |
| `users/index.tsx` | `/users` |
| `users/$id.tsx` | `/users/:id` (dynamic — bare `$`, no curly braces) |
| `posts/{-$category}.tsx` | `/posts/:category?` (optional segment) |
| `files/$.tsx` | `/files/*` (splat — read via `_splat` param, never `*`) |
| `_layout.tsx` | layout route (renders children via `<Outlet />`) |
| `__root.tsx` | app shell — wraps every page; preserve `<Outlet />` |

`routeTree.gen.ts` is auto-generated. Don't edit it by hand.
