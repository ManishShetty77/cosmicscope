# CosmicScope – Frontend Application

This folder contains the frontend code for the **CosmicScope Space Exploration Portal**.
The frontend provides the user interface that allows users to explore astronomy data, interact with the API, and manage their accounts.

The application communicates with the backend server to fetch space-related datasets such as asteroids, exoplanets, space weather events, and astronomy pictures.

---

# Project Information

This project is part of the **CosmicScope full-stack web application**, designed as an educational space exploration portal.

Users can:

* Browse astronomy datasets
* View space events and space weather
* Explore exoplanets and asteroids
* Save favorite items
* Access additional features through user login and admin roles

---

# Running the Project Locally

Make sure **Node.js and npm** are installed before running the project.

## 1. Clone the Repository

```id="a8t3dj"
git clone <YOUR_GIT_URL>
```

## 2. Open the Project Folder

```id="2v8fxb"
cd <YOUR_PROJECT_NAME>
```

## 3. Install Dependencies

```id="ix5a6p"
npm install
```

## 4. Start Development Server

```id="d8cbcs"
npm run dev
```

The development server will start and provide a local preview of the application.

---

# Editing the Project

You can edit the project using any modern code editor such as **Visual Studio Code**.

Typical workflow:

1. Open the project folder
2. Modify components, styles, or pages
3. Save the file
4. Refresh the browser to see changes

---

# Technologies Used

The frontend is built using modern web development tools:

* React
* Vite
* TypeScript
* Tailwind CSS
* UI component libraries

These tools provide a fast development environment and a responsive user interface.

---

# Deployment

To deploy the frontend application:

1. Build the project

```id="i3p7af"
npm run build
```

2. The build output will be generated in the **dist** folder.

3. The backend server serves the built frontend files when the application runs in production.

---

# Notes

* The frontend communicates with the backend API running on **http://localhost:3001**.
* Make sure the backend server is running before accessing the application.
