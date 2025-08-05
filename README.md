# InceptiX – "The Beginning of Esports Monetization"
[Simulate. Predict. Monetize]


game-insights-platform/
│
├── 📂 backend/                     # Node.js backend server
│   ├── index.js                   # Entry point
│   ├── routes/                    # API routes
│   │   ├── gameRoutes.js
│   │   └── mlRoutes.js
│   ├── controllers/               # Controller logic
│   ├── services/                  # DB queries, ML triggers
│   ├── config/                    # DB connection config
│   └── utils/                     # Helper functions
│
├── 📂 frontend/                   # Frontend app (React or static HTML)
│   ├── public/                    # HTML, favicon, assets
│   ├── src/
│   │   ├── components/            # Reusable UI components
│   │   ├── pages/
│   │   │   ├── Dashboard.js       # Embedded Power BI iframe
│   │   │   └── MLResults.js       # Show ML predictions
│   │   └── App.js
│   └── powerbi/                   # Optional: Embed SDK, bookmarks logic
│
├── 📂 sql/                        # SQL scripts & schema
│   ├── schema.sql                # Table creation
│   ├── seed.sql                  # Sample data
│   └── views.sql                 # Reusable SQL views for Power BI
│
├── 📂 python-ml/                  # Python for ML training/inference
│   ├── preprocessing.py          # Clean and transform data
│   ├── model_train.py            # Train ML model
│   ├── predict.py                # Use trained model
│   └── db_connect.py             # Read/write from PostgreSQL
│
├── 📂 powerbi/                    # Power BI assets
│   ├── reports/                  # Exported report screenshots or PDFs
│   └── embed_links.txt           # Page-level links or bookmarks
│
├── 📂 docs/                       # Documentation
│   ├── architecture-diagram.png
│   └── setup.md
│
├── .env                          # Environment variables (DB creds etc.)
├── .gitignore
├── README.md
└── package.json                  # For Node.js backend
