# 🍕 Crusty Corner

**Crusty Corner** is a modern, responsive pizza ordering web application built with React and Vite. Users can browse a delicious pizza menu, manage their cart, and place orders with a seamless and intuitive user experience.

*(Live Demo: https://crusty-corner.vercel.app/)*

## Features

- 🍕 Browse a beautifully designed pizza menu with images, prices, and ingredients
- 🛒 Add/remove pizzas to/from the cart
- 🔢 Update item quantities directly in the cart
- ✅ Real-time cart total calculation
- 👤 User name setup before placing an order
- 📱 Fully responsive design (mobile, tablet, desktop)
- ⚡ Fast navigation using React Router DOM
- 🌐 State management with Redux Toolkit
- 🎨 Styled with Tailwind CSS for a modern, clean look
- 🗂 Feature-based folder structure for excellent scalability and maintainability

## Tech Stack

- **React** (18+)
- **Vite** – Lightning-fast build tool and development server
- **Redux Toolkit** + **React Redux** – Predictable state management
- **React Router DOM** (v6) – Declarative routing
- **Tailwind CSS** – Utility-first CSS framework


## Installation

```bash
git clone https://github.com/your-username/crusty-corner.git
cd crusty-corner
npm install
```

## Run Locally

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

## Build for Production

```bash
npm run build
```

The production-ready files will be generated in the `dist/` folder.

## Preview Production Build Locally

```bash
npm run preview
```

## Project Structure

```
src/
├── app/              # App-wide configuration (store, router)
│   ├── store.js
│   └── router.jsx
├── features/         # Feature-based modules (scalable structure)
│   ├── menu/         # Menu page, loader, components
│   ├── cart/         # Cart page, components, slice
│   ├── order/        # Order creation & search pages
│   └── user/         # User name slice & component
├── ui/               # Reusable UI components (CartItem, Button, etc.)
├── utils/            # Helper functions (formatCurrency, etc.)
├── assets/           # Images and static assets
├── App.jsx
├── main.jsx
└── index.css         # Tailwind base + global styles
```

## Author

**Gourav Mishra**  
GitHub: [@Gouravmishra92](https://github.com/Gouravmishra92)  
LinkedIn: [Gourav Mishra](https://linkedin.com/in/gourav-mishra-09372a2ab/)

---

⭐ If you found this project helpful, please give it a star! It means a lot. 🍕
