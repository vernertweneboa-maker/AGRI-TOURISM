 Agri-Tourism WebsiteA modern, responsive platform built with React, Vite, and Tailwind CSS that connects travelers with unique farm-stay experiences . The project features a full navigation system and is integrated with Firebase for backend services.📂 Project StructureThis repository is organized as follows :src/pages/: Contains the main views: Home, Experiences, Booking, and Gallery .src/components/: Contains reusable UI elements like the Navbar .src/firebase.js: Handles the connection to the Firebase database and services.vercel.json: Configuration file to handle routing and prevent 404 errors on deployment.🛠️ Installation & SetupClone the Repo:Bashgit clone <your-new-github-link>
Install Dependencies:Bashnpm install
Environment Variables:
Create a .env file in the root directory and add your specific Firebase credentials :Code snippetVITE_FIREBASE_API_KEY=YOUR_API_KEY
VITE_FIREBASE_AUTH_DOMAIN=YOUR_AUTH_DOMAIN
VITE_FIREBASE_PROJECT_ID=YOUR_PROJECT_ID
VITE_FIREBASE_STORAGE_BUCKET=YOUR_STORAGE_BUCKET
VITE_FIREBASE_MESSAGING_SENDER_ID=YOUR_MESSAGING_SENDER_ID
VITE_FIREBASE_APP_ID=YOUR_APP_ID
🚀 Running LocallyTo start the development server with hot-reloading:Bashnpm run dev
🌐 DeploymentThis project is optimized for Vercel.The vercel.json file includes a "rewrites" rule that redirects all paths to index.html.This ensures that refreshing the page on routes like /Booking or /Experiences does not result in a "404 Not Found" error.
