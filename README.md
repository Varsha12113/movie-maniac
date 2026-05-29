Movie ManiacMovie Maniac is a fast, responsive, frontend-only React web application built with Vite. It allows users to discover real-time movies, browse by categories using customized filters, and seamlessly toggle between light and dark themes. The application fetches live data directly from the IMDb API to provide up-to-date movie information.🚀 FeaturesReal-Time Data: Fetches live movie details directly using the IMDb API.Category Filtering: Browse and sort movies easily via the integrated filter groups.Theme Toggle: Smooth switching between Light Mode and Dark Mode interfaces.Pure Frontend: Built entirely with React.js using client-side state management; no backend required.Vite-Powered: Optimized build tooling for blazing fast development and performance.🛠️ Tech StackBuild Tool: ViteFramework: React.js (JSX)Styling: Vanilla CSS (Component-scoped stylesheets)📦 Installation & SetupFollow these steps to run the project locally on your machine.PrerequisitesEnsure you have Node.js and npm installed.StepsClone the Repositorybashgit clone https://github.com
cd moviemanic
Use code with caution.Install Dependenciesbashnpm install
Use code with caution.Set Up Environment VariablesCreate a .env file in the root directory and add your IMDb API key:envVITE_IMDB_API_KEY=your_api_key_here
Use code with caution.Start the Development Serverbashnpm run dev
Use code with caution.Open the local URL provided in your terminal (usually http://localhost:5173) to view it in your browser.📂 Project StructuretextMOVIEMANIC/
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
📜 LicenseThis project is licensed under the MIT License.
