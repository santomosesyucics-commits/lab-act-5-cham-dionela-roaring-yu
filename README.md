# lab-act-5-cham-dionela-roaring-yu
Vue Login Lab
A Vue 3 authentication demo application with login functionality using DummyJSON API.

Features
Vue 3 + Vite + Pinia + Vue Router

Bootstrap 5 for styling

JWT Authentication with DummyJSON API

Protected Routes with navigation guards

Persistent Login using localStorage

Auto-logout on token expiration (401 responses)

src/
├── pages/
│   ├── HomePage.vue      # Public landing page
│   ├── LoginPage.vue     # Login form
│   └── DashboardPage.vue # Protected user dashboard
├── components/
│   └── AppNavbar.vue     # Navigation with auth state
├── stores/
│   └── auth.js          # Pinia store for authentication
├── api/

Test Credentials
Use these credentials to test the login:

Username: emilys

Password: emilyspass

Milestones Completed
✅ Vue 3 + Vite setup

✅ Bootstrap integration

✅ Vue Router with 3 pages

✅ Pinia state management

✅ Navigation guards

✅ DummyJSON login API integration

✅ Axios interceptors for auth

✅ Protected dashboard with user data


│   └── http.js          # Axios client with interceptors
└── router/
    └── index.js         # Route definitions and guards
