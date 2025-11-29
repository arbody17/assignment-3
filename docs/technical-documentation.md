# 🌐 Personal Portfolio – Assignment 3  

A personal portfolio website built using **HTML**, **CSS**, and **JavaScript**.  
This version (Assignment 3) expands the project with **API integrations**, **advanced logic**, enhanced **state management**, and a more polished and dynamic user experience.  

The website showcases my projects, skills, and contact information through a modern, interactive, and fully responsive design.

---

## ✨ Features  

### 🎨 UI & Interactivity  
- 📱 **Responsive Design** — Built using CSS Grid & Flexbox for full compatibility across phones, tablets, and desktops.  
- 🌗 **Dark/Light Theme Toggle** — Saves user preference using `localStorage` so the website remembers your theme.  
- ⌨️ **Typing & Deleting Animation** — Dynamic greeting message with looping motivational phrases and personalized name support.  
- 😎 **Personalized Greeting** — Stores the visitor’s name and updates the greeting instantly on the next visit.  
- 💡 **Read More / Read Less Toggle** — Expands or collapses the About Me section smoothly.  
- 🖼️ **Improved Project Cards** — Hover animations, larger images, better spacing, and featured-card design when filtering.  
- 🔝 **Scroll-to-Top Button** — Quickly returns the user to the top of the page.  

### 🧠 Logic & State Management  
- 🔎 **Project Filtering & Sorting** — Filter by category (Web, AI, Research) and sort by newest/oldest using `data-*` attributes.  
- 💾 **Saved Preferences** — Filter & sort selections are saved using `localStorage`.  
- ⏱️ **Time-on-Site Timer** — Shows how long a visitor has been on the website.  
- 👣 **Visit Counter** — Counts how many times the visitor has opened the website.  

### 🌍 External API Integrations  
- 🐙 **GitHub API Integration** — Displays my latest repositories with description, stars count, and update date.  
- 💬 **Inspirational Quote Box** — Fetches a random quote from a quotes API.  
  - If the API fails, the site automatically uses a **local fallback quote**, ensuring reliability.  
- 🔁 **“New Quote” Button** — Allows the user to refresh and load another quote instantly.  

### 📧 Contact Form  
- ✔️ **Email Validation** using regular expressions  
- 📩 **Smart Domain Suggestions** such as `@gmail.com`, `@hotmail.com`, `@outlook.com`  
- 😂 **Funny Popup** after submitting the form, adding a friendly and fun touch  

---

## 📂 Folder Structure  

 



## 📂 Folder Structure
```
assignment-1/
├── README.md
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── script.js
├── assets/
│   └── images/
├── docs/
│   ├── ai-usage-report.md
│   └── technical-documentation.md
└── .gitignore

```


---


---

## ⚙️ How to Run  

This project is **fully front-end** (no backend setup required).  
You can run it locally in a browser or host it online (e.g., **GitHub Pages**, **Netlify**, or **Vercel**).  

### 🧩 Step 1 — Clone the Repository  
Open your terminal or command prompt and run:  
```bash
git clone https://github.com/arbody17/assignment-2.git
cd assignment-2
