# 🌐 SAMPLE-PORTFOLIO-WEB

### 👨‍💻 Developed by Anand Teja Dasari

A modern and responsive **personal portfolio website** built using **HTML and CSS**, showcasing profile details, skills, projects, and contact information.

---

## 📌 Project Overview

This project is a **single-page portfolio website** designed to present:

* Personal introduction
* Technical skills
* Project work
* Contact information

It follows a **clean UI design**, smooth layout structure, and basic responsiveness.

---

## 🚀 Features

✔️ Fixed navigation bar for easy access
✔️ Hero section with introduction
✔️ About section with profile details
✔️ Skills section with styled tags
✔️ Projects section with cards layout
✔️ Contact form UI
✔️ Footer with social links
✔️ Responsive design using media queries

---

## 🧠 Sections Breakdown

---

### 🔝 Navbar

* Fixed at top using `position: fixed`
* Navigation links scroll to sections:

  * About
  * Skills
  * Projects
  * Contact

---

### 🎯 Hero Section

* Full screen (`100vh`) layout
* Gradient background using:

```css
background: linear-gradient(135deg, #2193F6, #6dd5ed);
```

* Includes:

  * Name highlight
  * Short description
  * Call-to-action button

---

### 👤 About Section

* Two-column layout using Flexbox
* Includes:

  * Profile image (`cv img.png`)
  * Academic and skill details

---

### 🧩 Skills Section

* Displays skills using flex layout
* Styled skill tags:

  * Java
  * Python
  * HTML
  * CSS

---

### 💼 Projects Section

* Card-based UI design

* Includes:

  * Portfolio Website
  * Ebay Car Data Analysis
  * Fake Reviews Detection

* Hover effect:

```css
.card:hover {
    transform: translateY(-10px);
}
```

---

### 📬 Contact Section

* Simple form UI with:

  * Name
  * Email
  * Message
* Styled using column layout

---

### 🔚 Footer

* Copyright section
* Social links:

  * LinkedIn
  * GitHub

---

## 🎨 Technologies Used

* HTML5
* CSS3 (Flexbox, Media Queries)

---

## 📂 Project Structure

```
SAMPLE-PORTFOLIO-WEB/
│
├── index.html
├── styles.css
├── README.md
│
├── cv img.png
├── githubimg.jpg
├── linkedinimg.jpg
```

---

## ⚙️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/anandteja2030/SAMPLE-PORTFOLIO-WEB.git
```

2. Open the project folder

3. Run:

```bash
index.html
```

---

## 📱 Responsive Design

* Uses media query:

```css
@media (max-width: 768px)
```

* Adjusts:

  * Navbar layout
  * About section (column)
  * Project cards stacking

---

## 🌐 WEB LINK
* https://anandteja2030.github.io/SAMPLE-PORTFOLIO-WEB/

## 💡 Key Learnings

* Structuring a real portfolio layout
* Using Flexbox for layout design
* Creating reusable UI components
* Applying hover effects and transitions
* Building responsive web pages

---

## 📈 Future Improvements

* Add JavaScript functionality (form handling, animations)
* Add project links and live demos
* Improve UI with animations and effects
* Add dark mode
* Deploy using GitHub Pages

---

## 👨‍💻 Author

**Anand Teja Dasari**
AI & Data Science Student | **Aspiring Java Full Stack Developer**

* 🔗 LinkedIn: https://www.linkedin.com/in/anandteja2030/
* 💻 GitHub: https://github.com/anandteja2030

---

## ⭐ Final Note

This project represents a **beginner-to-intermediate level portfolio website** and serves as a strong base for building advanced UI projects.

If you like this project, consider ⭐ starring the repository!

---
