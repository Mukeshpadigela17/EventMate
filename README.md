# EventMate

# EventHub 🎟️

EventHub is a modern event discovery and ticket booking frontend built with React, Vite, and Tailwind CSS.  
Users can browse movies, concerts, drama, marathons, and more in a clean, responsive UI.

> Note: This is a frontend-only demo. You can plug in your own backend or API for real data and authentication.

---

## ✨ Features

- Browse events by category (Movies, Concerts, Drama, Marathons)
- Event listing page with filters via URL query (`?category=...`)
- Responsive layout optimized for desktop and mobile
- Modern dark UI using Tailwind CSS
- Basic auth screen (Sign in / Sign up placeholder)
- Simple, well-structured React component architecture

---

## 🛠 Tech Stack

- **React 18**
- **Vite** (Dev server & bundler)
- **React Router DOM** (Client-side routing)
- **Tailwind CSS** (Styling)

---

## 📁 Project Structure

text

eventhub/

  index.html
  
  package.json
  
  postcss.config.cjs
  
  tailwind.config.cjs
  
  vite.config.mts
  
  src/
  
    main.jsx
    
    App.jsx
    
    styles/
    
      index.css
      
    components/
    
      Navbar.jsx
      
      Footer.jsx
      
      Hero.jsx
      
      Stats.jsx
      
      WhyChoose.jsx
      
      Categories.jsx
      
      CallToAction.jsx
      
      EventList.jsx
      
      EventCard.jsx
      
    pages/
    
      Home.jsx
      
      Events.jsx
      
      Login.jsx
      
    data/
    
      events.js

---

## 🚀 Getting Started

### Prerequisites

- Node.js (LTS version recommended)
- npm or yarn

### Installation

bash
# Clone the repository
git clone https://github.com/<your-username>/eventhub.git
cd eventhub

# Install dependencies
npm install


### Development

bash
npm run dev


Then open the URL shown in the terminal (usually `http://localhost:5173`) in your browser.

### Production Build

bash
npm run build
npm run preview


---

## 🧩 Configuration

You can tweak Tailwind and Vite configs:

- `tailwind.config.cjs` – Tailwind scan paths and custom theme colors
- `vite.config.mts` – Vite settings and dev server port
- `src/data/events.js` – Sample event data used for the listing page

---

## 📌 Next Steps / Ideas

- Connect to a real backend or Firebase for events and auth
- Add search, date filters, and pagination
- Integrate payment gateway for ticket booking
- Create organizer dashboard for event creation and management

---

## 🤝 Contributing

1. Fork the repository  
2. Create a new branch: `git checkout -b feature/my-feature`  
3. Commit your changes: `git commit -m "Add my feature"`  
4. Push to the branch: `git push origin feature/my-feature`  
5. Open a Pull Request

---

## 📄 License

This project is open source. You can use it as a starter for your own event booking application.  
Add your preferred license (MIT, Apache-2.0, etc.) here.
