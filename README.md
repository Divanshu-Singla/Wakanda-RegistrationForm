# 🐾 Wakanda Registration Form (Black Panther UI)

A **Marvel-inspired multi-step registration form** designed with a **Black Panther / Wakanda theme**, built using **HTML, CSS, and JavaScript**.  
The project focuses on **clean UI design, form validation, and storing user data in browser LocalStorage**.

---

## 🚀 Live Demo
🎥 Project Walkthrough (YouTube):  
https://youtu.be/BaI0uarjTYg

---

## 🖤 Project Theme
> *"Welcome to Wakanda! A true leader rises for the sake of others."*

This project uses a **dark, futuristic Wakandan UI** inspired by Marvel's **Black Panther**, giving a premium and immersive experience.

---

## ✨ Features

- 🔹 **Multi-Step Registration Form**
  - Part 1: Personal Details
  - Part 2: Security & Additional Details

- 🔹 **Modern UI Design**
  - Wakanda / Black Panther inspired theme
  - Dark mode styling with smooth transitions

- 🔹 **Form Validation**
  - Required field checks
  - Password confirmation validation

- 🔹 **LocalStorage Integration**
  - Stores user data securely in browser LocalStorage
  - No backend required

- 🔹 **Pure Frontend Project**
  - Built using only HTML, CSS, and JavaScript

---

## 🛠️ Tech Stack

| Technology | Usage |
|---------|------|
| HTML5 | Structure of the form |
| CSS3 | Styling & layout |
| JavaScript | Form logic & LocalStorage |
| LocalStorage | Client-side data storage |

---

## 📂 Project Structure

```
wakanda-registration-form/
│
├── index.html
├── style.css
├── script.js
├── assets/
│   ├── images/
│   └── icons/
└── README.md
```

---

## 🧠 How It Works

1. User fills **Part 1** (Basic Details)
2. Clicks **Next** to move to **Part 2**
3. User enters contact & password details
4. On submit:
   - Data is validated
   - Stored in **LocalStorage**
   - Form submission completes without backend

---

## 💾 LocalStorage Example

```js
localStorage.setItem("wakandaUser", JSON.stringify(userData));
```
