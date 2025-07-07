# Chatbot React App

This is a React-based chatbot application bootstrapped with [Vite](https://vitejs.dev/).

## 📁 Project Structure

```
chatbot/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   └── react.svg
│   ├── components/
│   │   ├── LoadingSpinner.jsx
│   │   └── ProtectedRoute.jsx
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── Login.jsx
│   │   └── SignUp.jsx
│   ├── App.css
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
├── vite.config.js
├── eslint.config.js
└── pnpm-lock.yaml
```

## 🚀 Getting Started

### Prerequisites

- Node.js (>= 14)
- npm or pnpm

### Install dependencies

Using npm:
```bash
npm install
```

Using pnpm:
```bash
pnpm install
```

### Run the development server

```bash
npm run dev
```

Visit `http://localhost:5173` in your browser.

## 🛠 Scripts

- `npm run dev` – Start development server
- `npm run build` – Build for production
- `npm run preview` – Preview production build
- `npm run lint` – Lint code with ESLint

## 🧩 Tech Stack

- React
- Vite
- JSX
- ESLint

## 📄 License

This project is licensed. See `LICENSE` file (if provided).

---

### 🧠 Notes

- `ProtectedRoute.jsx` likely manages route protection for authenticated pages.
- Pages like `Login.jsx` and `SignUp.jsx` indicate authentication flow.