<div align="center">
  <h1>Caffeinatic</h1>
  <p>A React.js and Firebase application for tracking coffee consumption and caffeine levels throughout the day with a clean, responsive UI.</p>
  <p>
    <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
    <img src="https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E" alt="Vite">
    <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase">
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
    <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS">
    <img src="https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white" alt="Netlify">
  </p>
</div>

## Features

- **User Authentication**: Secure sign-up and login functionality using Firebase Authentication
- **Coffee Tracking**: Add and monitor your coffee consumption with details like type, cost, and time of consumption
- **Caffeine Calculation**: Automatically calculates current caffeine levels in your system based on a 5-hour half-life
- **Historical Data**: View your coffee consumption history with detailed statistics
- **Interactive UI**: Clean, responsive interface built with Tailwind CSS and custom components

## Technologies Used

- **Frontend**: React.js, JSX
- **Styling**: Tailwind CSS, custom CSS
- **Backend**: Firebase (Authentication, Firestore)
- **Build Tool**: Vite
- **Deployment**: Netlify

## Getting Started

### Prerequisites
- Node.js (v14+)
- npm or yarn

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/caffeinatic.git
   cd caffeinatic
   ```
2. Install dependencies
   ```bash
   npm install
   ```
3. Create a ```.env``` file in the root directory with your Firebase configuration:
   ```bash
   VITE_FIREBASE_APIKEY=your-api-key
   VITE_FIREBASE_AUTHDOMAIN=your-auth-domain
   VITE_FIREBASE_PROJECTID=your-project-id
   VITE_FIREBASE_STORAGEBUCKET=your-storage-bucket
   VITE_FIREBASE_MESSAGINGSENDERID=your-messaging-sender-id
   VITE_FIREBASE_APPID=your-app-id
   ```
4. Start the development server
   ```bash
   npm run dev
   ```
### Deployment
Build the project for production :
```bash
npm run build
```
The built files will be in the ```dist``` directory, ready to be deployed to Netlify or your preferred hosting provider.

   
