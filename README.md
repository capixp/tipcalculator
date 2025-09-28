# TipCalculator

A simple **Tip and Bill Calculator** built with **React**, **TypeScript**, **Vite**, and **Tailwind CSS**.

---

## 🛠 Tech Stack

- **React** — UI library for building interactive interfaces  
- **TypeScript** — static typing for JavaScript  
- **Vite** — fast bundler and development server  
- **Tailwind CSS** — utility-first CSS framework  
- **Custom Hooks** — reusable stateful logic (e.g., `useOrder`)  
- **Modular Components** — `MenuItem`, `OrderContents`, `OrderTotals`, `TipPercentageForm`, etc.  
- **PostCSS** — CSS post-processing (integrated with Tailwind)  
- **ESLint** — linting and code quality rules  
- **Configuration files**:  
  - `tsconfig.json`, `tsconfig.app.json`, `tsconfig.node.json`  
  - `vite.config.ts`  
  - `tailwind.config.js`, `postcss.config.js`  

---

## 🚀 Live Demo

👉 [Click here to try the app](https://your-demo-link.netlify.app)  

*(Replace with your actual Netlify, Vercel, or GitHub Pages link once deployed)*

---

## 🚀 Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/capixp/tipcalculator.git
   cd tipcalculator

2. Install dependencies:
   
npm install

3.Run the development server:

npm run dev

📂 Project Structure

.
├── public/
├── src/
│   ├── components/
│   │   ├── MenuItem.tsx
│   │   ├── OrderContents.tsx
│   │   ├── OrderTotals.tsx
│   │   └── TipPercentageForm.tsx
│   ├── data/
│   │   └── db.ts
│   ├── helpers/
│   │   └── index.ts
│   ├── hooks/
│   │   └── useOrder.ts
│   ├── types/
│   │   └── index.ts
│   ├── main.tsx
│   └── index.css
├── tailwind.config.js
├── postcss.config.js
├── vite.config.ts
├── tsconfig*.json
├── package.json
├── .gitignore
└── README.md

components/: UI components

data/db.ts: mock data / menu items

helpers/: utility functions

hooks/: custom React hooks (business logic)

types/: TypeScript type definitions

Config files for Tailwind, Vite, and TypeScript

| Command           | Description                           |
| ----------------- | ------------------------------------- |
| `npm run dev`     | Start the dev server with hot reload  |
| `npm run build`   | Build an optimized production version |
| `npm run preview` | Preview the production build locally  |
| `npm run lint`    | Run ESLint checks (if configured)     |

✅ Best Practices

Use custom hooks to encapsulate state and logic

Keep components small and reusable

Define explicit TypeScript types for props and state

Use Tailwind utility classes consistently

Follow ESLint rules and formatting for clean code

📤 Deployment
Netlify

Push your project to GitHub.

Log in to Netlify




