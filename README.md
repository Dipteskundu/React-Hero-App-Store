# React Apps Store (HERO Apps)

## Overview
A simple app store-style web app to browse, search, view details, and manage (mock) installations of React-based applications. It features a clean layout with a home banner, searchable app list, detailed app pages with charts, and a lightweight installation manager backed by `localStorage`.

## Live Demo
- Live app: https://react-hero-app-store.netlify.app/

## Screenshot
<img align="center" width="60%" src="https://i.ibb.co.com/NgSKwpSY/Screenshot-2025-11-27-155908.png" alt="Screenshot of hero-apps-store">
```

## Tech Stack
- React 19
- Vite 7
- React Router 7
- Tailwind CSS 4
- DaisyUI 5
- Recharts
- React Toastify
- ESLint

## Core Features
- Browse a curated list of React-based applications in an app-store-style layout.
- View detailed app pages with charts and key metrics for each app.
- Search and filter apps to quickly find what you are looking for.
- Install/uninstall apps (mock installs) with state persisted in `localStorage`.
- Responsive UI built with Tailwind CSS and DaisyUI components.
- Toast notifications for key actions such as installs or removals.

## Dependencies
- Runtime:
  - `react`, `react-dom`
  - `react-router`, `react-router-dom`
  - `tailwindcss`, `@tailwindcss/vite`
  - `recharts`
  - `react-toastify`
- Development:
  - `vite`, `@vitejs/plugin-react`
  - `eslint`, `@eslint/js`, `eslint-plugin-react-hooks`, `eslint-plugin-react-refresh`, `globals`
  - `@types/react`, `@types/react-dom`
  - `daisyui`

## Running the Project Locally
1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   ```
2. Navigate into the project directory:
   ```bash
   cd React-Hero-App-Store
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```
5. Open the app in your browser (Vite default):
   - http://localhost:5173/

6. Build for production (optional):
   ```bash
   npm run build
   ```
7. Preview the production build (optional):
   ```bash
   npm run preview
   ```

## Additional Resources

- React documentation: https://react.dev
- Vite documentation: https://vite.dev
