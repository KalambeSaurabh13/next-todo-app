/my-next-app
│── 📂 public            # Static assets (images, icons, fonts)
│── 📂 src               # Main source directory
│   │── 📂 components    # Reusable UI components
│   │   │── 📂 common    # Shared UI components (Button, Modal, Loader)
│   │   │── 📂 layout    # Layout components (Header, Footer, Sidebar)
│   │   │── 📂 features  # Feature-specific components
│   │   └── index.js     # Export all components
│   │── 📂 pages         # Next.js pages (Routes)
│   │   │── 📂 api       # API routes (Next.js serverless functions)
│   │   │── _app.js      # Custom App component (for Redux & global styles)
│   │   │── _document.js # Custom Document component (for meta tags)
│   │   │── index.js     # Home page
│   │   └── about.js     # Other pages
│   │── 📂 redux         # Redux state management
│   │   │── 📂 slices    # Redux slices (authSlice.js, userSlice.js)
│   │   │── store.js     # Redux store configuration
│   │   └── hooks.js     # Custom hooks for Redux
│   │── 📂 styles        # Global styles (CSS, Tailwind, or SCSS)
│   │── 📂 utils         # Utility functions (helpers, API calls)
│   │── 📂 hooks         # Custom React hooks
│   └── 📂 config        # Config files (API endpoints, constants)
│── .gitignore
│── package.json
│── next.config.js
│── README.md


----------------------------------------------------------------------------------------------

/my-next-app
│── 📂 public            # Static assets (images, icons, fonts)
│── 📂 src               # Main source directory
│   │── 📂 app           # App Router (New Next.js routing)
│   │   │── 📂 api       # API routes (server-side functions)
│   │   │── 📂 dashboard # Example page folder
│   │   │   ├─ page.js   # Dashboard page
│   │   │   ├─ layout.js # Layout for dashboard pages
│   │   │── layout.js    # Root layout
│   │   │── page.js      # Home page (root)
│   │── 📂 components    # Reusable UI components
│   │   │── 📂 common    # Shared UI components (Button, Modal, Loader)
│   │   │── 📂 layout    # Layout components (Header, Footer, Sidebar)
│   │   │── 📂 features  # Feature-specific components
│   │── 📂 redux         # Redux Toolkit (RTK Query)
│   │   │── 📂 slices    # Redux slices (authSlice.js, userSlice.js)
│   │   │── apiSlice.js  # RTK Query API setup
│   │   │── store.js     # Redux store configuration
│   │   └── hooks.js     # Custom hooks for Redux
│   │── 📂 styles        # Global styles (CSS, Tailwind, or SCSS)
│   │── 📂 hooks         # Custom React hooks
│   │── 📂 utils         # Utility functions (helpers, API calls)
│   │── 📂 config        # Config files (API endpoints, constants)
│── .gitignore
│── package.json
│── next.config.js
│── README.md
