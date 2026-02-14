# 🌍 WORLD ATLAS 🌎  

<p align="center">
  <b>✨ Explore the World, One Country at a Time ✨</b><br/>
  A modern ⚛️ React application to discover countries, cultures, and real-time 🌐 data worldwide.
</p>

---

## 🔗 🚀 Live Demo  

👉 https://world-atlas-sepia-sigma.vercel.app/

---

## 📖 🌟 About The Project  

**WorldAtlas** is a fully responsive 📱 React application that allows users to explore real-time country data from around the world 🌎.

Users can:

- 🌎 Browse all countries  
- 🔍 Search countries instantly  
- 🌍 Filter by region  
- 🔤 Sort alphabetically (A → Z / Z → A)  
- 📄 View detailed country information  
- 🚦 Navigate dynamically between pages  

The application fetches live data from the 🌐 **REST Countries API** and displays it using a clean 🧩 component-based architecture.

---

## 🚀 🛠 Tech Stack  

- ⚛️ React (Vite)  
- 🔁 React Router DOM  
- 📡 Axios  
- 🌍 REST Countries API  
- 🎨 CSS3  

---

## 📂 🗂 Project Structure  

```
world-atlas/
│
├── public/
│   └── images/
│
├── src/
│   ├── api/
│   │   ├── countryData.json
│   │   ├── footerApi.json
│   │   └── postApi.jsx
│   │
│   ├── assets/
│   │   └── react.svg
│   │
│   ├── components/
│   │   ├── Layout/
│   │   │   ├── AppLayout.jsx
│   │   │   ├── CountryCard.jsx
│   │   │   └── CountryDetails.jsx
│   │   │
│   │   └── UI/
│   │       ├── Headers.jsx
│   │       ├── Footers.jsx
│   │       ├── HeroSection.jsx
│   │       ├── Loader.jsx
│   │       └── SearchFilter.jsx
│   │
│   ├── pages/
│   │   ├── About.jsx
│   │   ├── Contact.jsx
│   │   ├── Country.jsx
│   │   ├── ErrorPage.jsx
│   │   └── Home.jsx
│   │
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   └── main.jsx
│
├── .gitignore
├── README.md
├── index.html
├── package.json
└── package-lock.json
```

---

## 🧠 🏗 Architecture Overview  

The project follows a clean modular architecture:

- 📡 `api/` → API calls and static data  
- 🧱 `components/Layout/` → Layout-based reusable components  
- 🎨 `components/UI/` → Small reusable UI components  
- 📄 `pages/` → Route-level components  
- 🛣 `App.jsx` → Routing configuration  
- 🚀 `main.jsx` → React entry point  

This structure improves scalability 📈, maintainability 🔧, and code reusability ♻️.

---

## ⚙️ 🔍 How It Works  

1️⃣ Axios fetches data from REST Countries API 🌍  
2️⃣ Data is stored using React state ⚛️  
3️⃣ Search and filter dynamically update the country list 🔎  
4️⃣ Sorting uses JavaScript `localeCompare()` 🔤  
5️⃣ Clicking a country navigates to a dynamic route `/country/:id` 🛣  

---

## 👨‍💻 🙌 Author  

**Himanshu Ranjan**

🔗 LinkedIn: https://www.linkedin.com/in/imhr07/  
🔗 GitHub: https://github.com/imhr45  

---

⭐ If you like this project, give it a star and support the journey! 🚀✨
