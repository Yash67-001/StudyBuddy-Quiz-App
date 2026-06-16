# StudyBuddy - Interactive Engineering Quiz

A fast, lightweight, and fully responsive frontend quiz application built for testing Computer Science fundamentals. Developed as a college end-semester project focusing on pure logic, state management, and modern UI/UX design without the need for external libraries or a backend API.

## ✨ Features

* **Zero-Dependency Architecture:** Built entirely with vanilla HTML, CSS, and JavaScript.
* **Multi-Category Quizzes:** Four distinct modules including OOPs, JavaScript, Data Structures & Algorithms, and a Master Mix.
* **Persistent State Management:** Uses `localStorage` to save user login, global scores, total questions answered, and category-specific personal bests.
* **Dynamic Theming Engine:** Toggle between **Dark**, **Light**, and **Midnight** (OLED) modes. Theme preferences are automatically saved across sessions.
* **Interactive Timer:** 15-second countdown per question featuring a visual pulse warning for the final 5 seconds. Timeout automatically reveals the correct answer.
* **Modern Glassmorphism UI:** Clean, translucent card designs with dynamic gradient backgrounds.
* **iOS-Style Mobile Navigation:** The top navigation bar transforms into a sleek, floating bottom dock on mobile devices for ergonomic thumb reach.
* **Accessibility (a11y) Focused:** Includes `aria-live` regions for screen readers, clear `:focus-visible` states for keyboard navigation, and semantic HTML structure.
* **Double-Click Protection:** Logic locks prevent spam-clicking or double-counting scores during timer transitions.

## 🛠️ Tech Stack

* **HTML5:** Semantic structure and accessibility.
* **CSS3:** Custom variables, CSS Grid/Flexbox, backdrop-filters, media queries, and keyframe animations.
* **JavaScript (ES6+):** DOM manipulation, state variables, event delegation, and `localStorage` API.

## 🚀 How to Run

Because this project is built entirely on frontend web standards with no build tools or backend requirements, setup is instantaneous.

1.  Clone this repository or download the source code.
2.  Locate the `index.html` file on your machine.
3.  Double-click `index.html` to open it in any modern web browser (Chrome, Firefox, Safari, Edge).

## 📱 Responsive Design Breakdown

* **Desktop (769px and above):** Features a fixed top navigation bar, 2-column grid layout for quiz options, and centered content.
* **Mobile (768px and below):** Transforms the navigation into a floating bottom dock, converts options to a single-column layout, and expands tap targets (min 60px height) for comfortable touch interaction.
