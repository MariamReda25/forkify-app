# 🍴 Forkify App

A modern recipe management web application that allows users to search for recipes, view cooking instructions, bookmark their favorites, and even upload their own recipes — all powered by asynchronous JavaScript and a clean MVC architecture.

---

## 🚀 Project Overview

**Forkify** is a single-page web application (SPA) built using modern JavaScript (ES6+), following the **Model-View-Controller (MVC)** architecture.  
It interacts with the **Forkify API** to fetch real-time recipe data, display search results, handle pagination, manage bookmarks using local storage, and allow users to upload new recipes.

This project demonstrates advanced front-end development concepts such as:

- Asynchronous programming with `async/await`
- Application state management
- DOM updates and virtual rendering
- Data persistence using local storage
- Modular JavaScript and build automation with Parcel

---

## 🧰 Tech Stack

| Category                    | Technology                                   |
| --------------------------- | -------------------------------------------- |
| **Language**                | JavaScript (ES6+)                            |
| **Architecture**            | MVC (Model–View–Controller)                  |
| **Bundler**                 | [Parcel](https://parceljs.org/)              |
| **API**                     | [Forkify API](https://forkify-api.jonas.io/) |
| **Styling**                 | CSS3 / Sass                                  |
| **Version Control**         | Git & GitHub                                 |
| **Development Environment** | Visual Studio Code, PowerShell / Git Bash    |

---

## 🧠 Architecture

The app follows a **modular MVC architecture** for maintainability and scalability.

![Forkify App Architecture Flowchart](./forkify-flowchart-part-3.png)

### Core Components:

- **Model:**  
  Handles data fetching, application state, and business logic (API calls, bookmarks, uploads).
- **View:**  
  Responsible for rendering UI components such as recipe view, search results, pagination, and bookmarks.
- **Controller:**  
  Connects Model and View — handles events, updates state, and triggers re-rendering.

### Data Flow Summary:

1. User searches for a recipe → async API call fetches data → results rendered.
2. User selects a recipe → recipe data loaded and displayed.
3. Bookmarks are stored in and loaded from local storage.
4. Users can upload their own recipes → sent to API → rendered in app.

---

## ✨ Features

- 🔍 **Search Recipes:** Fetch thousands of recipes from the Forkify API.
- 🍽️ **View Recipe Details:** Ingredients, time, servings, and publisher info.
- 🧮 **Adjust Servings:** Dynamically update ingredient quantities.
- ❤️ **Bookmark Recipes:** Save favorites in local storage for persistence.
- 📄 **Upload Recipes:** Add custom recipes and share them through the API.
- ⏩ **Pagination:** Navigate through large result sets smoothly.
- ⚡ **Responsive Design:** Works seamlessly on desktop and mobile.
- 🧩 **Modular Codebase:** Organized with ES6 modules and MVC pattern.

## 🧭 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/MariamReda25/forkify-app
cd forkify-app
```

### 2️⃣ Install Dependencies

```bash
 npm install
```

### 3️⃣ Run the Development Server

```bash
npm start
```

### 4️⃣ Build for Production

```bash
npm run build
```

## 📌 Project link on Vercel :

[Live Demo ](https://forkify-app-pi.vercel.app/)

💡 This project was inspired by Jonas Schmedtmann’s “The Complete JavaScript Course”
