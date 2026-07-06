# 🎬 Stream Hotspot – custom Captive Portal UI for Mikrotik and openwrt router network

![Image](https://jumagemini.github.io/screenshots/dashboard.png "Captive Portal Dashboard UI")

**Live Demo:** [https://jumagemini.github.io/](https://jumagemini.github.io/)

**Portfolio Showcase:** A full‑featured, responsive web application that combines a captive portal, internet bandwidth management, movie streaming shop, cyber cafe services, and community chat – all in one elegant dark‑themed UI.

---

## 🚀 Overview

StreamVault is a frontend UI/UX portfolio project designed to demonstrate advanced frontend development skills. It simulates a real‑world captive portal environment for a WiFi hotspot, offering:

- Bandwidth management with package purchasing (MPESA STK push simulation).  
- Movie & series browsing with cart, checkout, and temporary download links.  
- Cyber cafe services (printing, scanning, government applications, technical support) with a file‑upload‑enabled service chat.  
- Community chat (Tubonge) where users can interact in real‑time (simulated).  

The interface is fully responsive, works on all screen sizes, and features a cohesive dark theme with smooth animations and intuitive navigation.

---

## ✨ Key Features

### 🌐 Internet Packages (Captive Portal)
- Real‑time bandwidth stats: total, used, available, active connections.  
- Four pre‑defined packages (2 Mbps/2hrs, 2 Mbps/24hrs, 3 Mbps/1 week, 5 Mbps/1 month).  
- Purchase flow with MPESA STK Push simulation (phone input, progress bar, confirm/cancel).  
- Automatic bandwidth allocation and countdown expiration.  
- Manual disconnect button.

### 🎥 Movie Shop
- Browse popular, upcoming, and series collections.  
- Search by title, genre, year, or type.  
- Interactive movie cards with detail modal, trailer (YouTube embed), and add‑to‑cart.  
- Cart with total calculation and checkout via MPESA.  
- After successful payment, a 12‑hour temporary download link is generated.

### 🖨️ Cyber Cafe Services
- Categorized services:  
  - **Document** (printing, scanning, lamination, etc.)  
  - **Government & Admin** (passport, driving license, KRA tax returns, company registration)  
  - **Technical Support** (software installation, computer rental, IT troubleshooting)  
  - **Additional** (passport photos, stationery, food)  
- Click any service to auto‑send a request in the service chat.  
- Service chat with file upload (multiple files) and auto‑replies from a virtual assistant.

### 💬 Tubonge – Community Chat
- Real‑time (simulated) chat room for all connected users.  
- Persistent message history using `localStorage`.  
- Randomly generated user names and occasional bot messages to simulate lively conversation.  
- Online user list (simulated).

---

## 🎨 UI/UX Highlights
- Fully responsive (mobile‑first) – adapts to any screen size.  
- Dark theme with accent colors, smooth hover effects, and micro‑interactions.  
- Sticky header with bandwidth indicator and cart badge.  
- Clean tabbed navigation (Internet / Movies / Cyber Cafe / Tubonge).  
- Toast notifications for user feedback.  
- Non‑intrusive session‑timed advertisement banner that rotates offers.

---

## 🛠️ Technologies Used
- **HTML5** – Semantic markup.  
- **CSS3** – Custom properties (CSS variables), Flexbox, CSS Grid, keyframe animations, media queries.  
- **JavaScript (Vanilla)** – ES6+ syntax, DOM manipulation, event handling, `localStorage` for persistence.  
- **Font Awesome** – Icons.  
- **Google Fonts (Inter)** – Typography.  
- **GitHub Pages** – Hosting.  

No external libraries or frameworks – pure frontend craftsmanship.

---

## 📸 Screenshots

| Internet Packages | Movies Tab | Cyber Cafe | Tubonge Chat |
|-------------------|------------|------------|--------------|
| [packages.png](https://jumagemini.github.io/screenshots/packages.png) | [packages.png](https://jumagemini.github.io/screenshots/movies.png) | [packages.png](https://jumagemini.github.io/screenshots/services.png) | [packages.png](https://jumagemini.github.io/screenshots/tubonge.png) |


---

## 🧪 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/jumagemini/jumagemini.github.io.git
   cd jumagemini.github.io
2. Open index.html in your browser (no build step required).
3. Explore all features – the app is fully self‑contained.

## 🔧 Customization Guide

### 📦 Modify Movies & Series
Edit the `MOVIES` and `SERIES` arrays in the JavaScript section (around line 1600) – update titles, descriptions, posters (use your own image URLs), prices, trailers, etc.

### 📶 Adjust Bandwidth & Packages
Change `TOTAL_BANDWIDTH` (line ~1620) and the `PACKAGES` array to fit your needs.

### 🛠️ Cyber Cafe Services
Update the service items in the HTML under `#tabServices` – each `.service-item` has `data-service` and `data-price` attributes for chat integration.

### 🗣️ Tubonge Chat Customization
- User name prompt can be disabled by removing the prompt in `tubongeUser` initialization.
- Simulated bot messages are defined in `TUBONGE_MESSAGES` and `KENYAN_NAMES` arrays.

### 🎨 Branding & Colors
All colors are defined in CSS variables under `:root`. Change the `--accent`, `--green`, `--gold`, etc., to match your brand.

### 📱 Responsive Breakpoints
- **Desktop:** Full layout with side panels and sticky chat.
- **Tablet (≤ 992px):** Layout stacks, chat panels shrink.
- **Mobile (≤ 768px):** Compact cards, hidden banner arrows, simplified headers.
- **Small Mobile (≤ 480px):** Minimal spacing, two‑column package cards.

---

## 🌟 Why This Project Stands Out
- **Complete Product Simulation** – Not just a static page, but a functional prototype with realistic flows (purchase, cart, chat, file upload, download links).
- **Attention to UI/UX** – Every interaction is polished: hover states, loading feedback, modal transitions, toast messages, and responsive adaptations.
- **Portfolio‑Ready** – Demonstrates mastery of vanilla HTML/CSS/JS without relying on frameworks, perfect for frontend developer roles.

---

## 📄 License
This project is open‑source and available under the **MIT License**. Feel free to use it as a reference for your own portfolio.

---

## 🙌 Acknowledgements
- Icons by [Font Awesome](https://fontawesome.com)
- Font by [Google Fonts](https://fonts.google.com)
- Placeholder images from [Picsum Photos](https://picsum.photos)

---

## 📬 Contact
Looking for a developer for an app? Feel free to reach out: 

- Email:  [Dennis Juma](mailto:jumagemini@gmail.com)
- LinkedIn: [Dennis Juma](https://linkedin.com/in/dennis-juma-969553125)
- Github: [Dennis Juma](https://github.com/jumagemini)

---

*Built with ❤️ to showcase frontend design and development skills.*