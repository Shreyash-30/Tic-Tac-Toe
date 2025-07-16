# Tic-Tac-Toe (React + Vite)

This project is a simple Tic-Tac-Toe game built with [React](https://react.dev/) and [Vite](https://vitejs.dev/).  
The main purpose of building this project is to understand the basics of React components, hooks, and props.

## Learning Goals

- **React Components:**  
  Learn how to structure UI using reusable components.

- **React Hooks:**  
  Practice using hooks like `useState` to manage state in functional components.

- **Props:**  
  Understand how to pass data and event handlers between components using props.

## Getting Started

1. **Install dependencies:**
   ```sh
   npm install
   ```

2. **Run the development server:**
   ```sh
   npm run dev
   ```

3. **Open in browser:**  
   Visit [http://localhost:5173](http://localhost:5173) (or the port shown in your terminal).

## Project Structure

- [`src/App.jsx`](src/App.jsx): Main app component.
- [`src/Components/Board.jsx`](src/Components/Board.jsx): Game board and logic.
- [`src/Components/Board.css`](src/Components/Board.css): Board styling.
- [`src/main.jsx`](src/main.jsx): Entry point for React rendering.

## Features

- Play Tic-Tac-Toe against another player.
- Displays current player and winner.
- Responsive and simple UI.

## License

This project is for educational purposes and is licensed under the MIT License. See `LICENSE` for details.

---

## React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
