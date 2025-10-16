# greg-arriaga.github.io
This readme file is meant for those interested in my code or accidently found this file. If the later, please visit https://greg-arriaga.github.io/

/
├── **.gitignore** # Files to ignore in version control
├── **package.json** # Project metadata and dependencies (for Node.js/tools)
├── **README.md** # Project description and setup instructions
├── **src/** # 📦 All your source code goes here
│   ├── **api/** # 📡 Server-side logic (e.g., REST endpoints, data handlers)
│   │   ├── **users.js**
│   │   └── **posts.js**
│   ├── **assets/** # 🖼️ Static resources (optimized for production)
│   │   ├── **fonts/**
│   │   ├── **images/**
│   │   └── **videos/**
│   ├── **components/** # 🧱 Reusable UI components (e.g., button, navbar, footer)
│   │   ├── **Button.js**
│   │   └── **Navbar.js**
│   ├── **config/** # ⚙️ Environment variables, constants, and global settings
│   │   └── **settings.js**
│   ├── **data/** # 💾 Mock data or static JSON/CSV files (if not using a DB)
│   ├── **helpers/** # 🛠️ Utility functions (e.g., date formatting, validation)
│   │   └── **validators.js**
│   ├── **pages/** # 📄 Application entry points/main views
│   │   ├── **Home.js**
│   │   ├── **About.js**
│   │   └── **Contact.js**
│   ├── **services/** # 🔗 Logic for external interactions (e.g., DB queries, API calls)
│   │   └── **db.js**
│   ├── **styles/** # 💅 CSS, SASS, or Less files
│   │   ├── **_variables.css**
│   │   ├── **global.css** # Base/reset styles
│   │   └── **pages/** # Page-specific styles
│   └── **App.js** # 🚀 Main application entry file (for front-end apps)
├── **public/** # 🌐 Files directly served by the web server (unprocessed)
│   ├── **index.html** # The main entry HTML file
│   └── **favicon.ico**
└── **dist/** or **build/** # 🏭 Output directory for the compiled/production code (ignored by git)
