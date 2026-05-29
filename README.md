# Movie Maniac

Movie Maniac is a fast, responsive, frontend-only React web application built with Vite. It allows users to discover real-time movies, browse by categories using customized filters, and seamlessly toggle between light and dark themes. The application fetches live data directly from the IMDb API to provide up-to-date movie information.

## 🚀 Features

* **Real-Time Data**: Fetches live movie details directly using the IMDb API.
* **Category Filtering**: Browse and sort movies easily via the integrated filter groups.
* **Theme Toggle**: Smooth switching between Light Mode and Dark Mode interfaces.
* **Pure Frontend**: Built entirely with React.js using client-side state management; no backend required.
* **Vite-Powered**: Optimized build tooling for blazing fast development and performance.

## 🛠️ Tech Stack

* **Build Tool**: Vite
* **Framework**: React.js (JSX)
* **Styling**: Vanilla CSS (Component-scoped stylesheets)

## 📦 Installation & Setup

Follow these steps to run the project locally on your machine.

### Prerequisites

Ensure you have **Node.js** and **npm** installed.

### Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com
   cd movie-maniac
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**
   Create a `.env` file in the root directory and add your IMDb API key:
   ```env
   VITE_IMDB_API_KEY=your_api_key_here
   ```

4. **Start the Development Server**
   ```bash
   npm run dev
   ```
   Open the local URL provided in your terminal (usually `http://localhost:5173`) to view it in your browser.

## 📂 Project Structure

```text
MOVIEMANIC/
├── node_modules/
├── public/
├── src/
│   ├── assets/               # Image and SVG assets (Sun, Moon, Stars, etc.)
│   ├── components/
│   │   ├── DarkMode/         # Dark mode toggle component and styles
│   │   │   ├── DarkMode.css
│   │   │   └── DarkMode.jsx
│   │   ├── Navbar/           # Navigation header bar component and styles
│   │   │   ├── MovieList/    # Movie listing, cards, and filtering logic
│   │   │   │   ├── FilterGroup.jsx
│   │   │   │   ├── MovieCard.css
│   │   │   │   ├── MovieCard.jsx
│   │   │   │   ├── MovieList.css
│   │   │   │   └── MovieList.jsx
│   │   │   ├── Navbar.css
│   │   │   └── Navbar.jsx
│   ├── App.css               # Main app layout styles
│   ├── App.jsx               # Root application component
│   ├── index.css             # Global styles
│   └── main.jsx              # Vite React entry point
├── .gitignore
├── eslint.config.js          # Linter configuration
├── package.json              # Project dependencies and scripts
└── README.md                 # Project documentation
```

## 📜 License

This project is licensed under the MIT License.
