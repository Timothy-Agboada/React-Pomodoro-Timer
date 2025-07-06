## 🚀 30-Day Coding Challenge: Day 28

This project is the twenty-eighth entry in my 30-day coding challenge. Today's goal was to rebuild the Pomodoro Timer from Day 8 using React. This exercise highlights the power and elegance of using React hooks (`useState`, `useEffect`) to manage time-based events and application state, resulting in more declarative and maintainable code.

### 📖 Project Overview

This is a modern and visually appealing Pomodoro timer designed to boost productivity. The application allows users to switch between "Work," "Short Break," and "Long Break" sessions. It features a large, clear countdown timer, standard controls (Start, Pause, Reset), and a dynamic theme that changes the background color to match the active session type. The entire application is built with React, showcasing how to properly manage intervals and side effects.

### ✨ Live Demo & Screenshot

Below is a screenshot of the application's interface.
![Jul-04-2025 18-44-50](https://github.com/user-attachments/assets/bcb98d12-221b-45cc-8773-d2c271773808)


### 🌟 Key Features

* **Multiple Timer Modes:** Easily switch between focused work sessions and short/long breaks.
* **Dynamic Theming:** The application's background color smoothly transitions to match the current session type (e.g., red for work, green for a short break).
* **`useEffect` for Timers:** Properly manages the countdown logic using `setInterval` within a `useEffect` hook, including a crucial cleanup function to prevent memory leaks.
* **Live Title Updates:** The browser tab's title updates in real-time to reflect the current countdown, even when the window is not active.
* **Full Timer Controls:** Includes Start, Pause, and Reset functionality for complete control over the session.
* **Component-Based:** A self-contained React component manages all the logic and rendering.

### 💻 Technologies Used

This project was built using a modern, lightweight React setup.

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Babel](https://img.shields.io/badge/Babel-%23F9DC3e.svg?style=for-the-badge&logo=babel&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

* **React:** The core library for building the user interface and managing state.
* **ReactDOM:** Used to render the React component into the browser's DOM.
* **Babel:** Used as a transpiler to convert JSX into standard JavaScript.
* **Tailwind CSS:** For all styling and layout.
* **Font Awesome:** For icons.

### 🛠️ How to Run Locally

This project is set up to be extremely simple to run, with no build process required:

1.  **Clone the repository (or download the code):**
    ```bash
    git clone https://github.com/timothy-agboada/react-pomodoro-timer.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd react-pomodoro-timer
    ```
3.  **Open the `index.html` file in your web browser.** The CDN links will handle loading all necessary libraries automatically.

### 🎯 Learning Objectives

This project was a practical exercise in several key React concepts:

* **Managing Intervals with `useEffect`:** Mastering the standard React pattern for using `setInterval` and `clearInterval` within a `useEffect` hook.
* **The `useEffect` Cleanup Function:** Understanding the critical importance of returning a cleanup function from `useEffect` to prevent bugs and performance issues when dealing with timers or subscriptions.
* **Multiple `useEffect` Hooks:** Using separate effects for different side effects (timer logic, document title, body class) to keep code organized and maintainable.
* **State-Driven UI:** Reinforcing the core concept that the UI is a direct reflection of the application's state.
