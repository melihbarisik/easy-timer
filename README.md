# Proje Yapısı

Bu proje, **React (Next.js) client** ve **Node.js (Express) server** içeren tam bir full-stack uygulamadır.

## 📁 Dizin Yapısı

```
project-root/
├── client/                  # Frontend React application
│   ├── public/
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/         # Page components/routes
│   │   ├── hooks/         # Custom React hooks
│   │   ├── services/      # API integration
│   │   ├── store/         # State management
│   │   ├── utils/         # Helper functions
│   │   ├── assets/        # Images, fonts, etc.
│   │   ├── styles/        # Global styles
│   │   └── App.jsx
│   └── package.json
│
├── server/                  # Backend Node.js application
│   ├── src/
│   │   ├── controllers/    # Request handlers
│   │   ├── models/        # Data models
│   │   ├── routes/        # API routes
│   │   ├── services/      # Business logic
│   │   ├── middleware/    # Custom middleware
│   │   ├── utils/         # Helper functions
│   │   └── config/        # Configuration files
│   └── package.json
│
└── package.json            # Root package.json for project-wide scripts
```
