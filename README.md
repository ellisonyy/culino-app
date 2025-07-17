# Culino App

A React Native mobile application built with Expo, featuring Firebase authentication and a Node.js backend.

## 🏗️ Project Structure

```
culino-app-1/
├── frontend/          # Expo React Native app
│   ├── app/          # Expo Router screens
│   │   ├── (auth)/   # Authentication screens
│   │   ├── (tabs)/   # Main app tabs
│   │   └── _layout.tsx
│   ├── assets/       # Images, fonts, etc.
│   ├── firebaseConfig.ts
│   └── package.json
├── backend/          # Node.js/Express server
│   ├── index.js
│   └── package.json
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v18+)
- npm or yarn
- Expo CLI
- Expo Go app on your phone

### Frontend Setup
```bash
cd frontend
npm install
npx expo start --lan
```

### Backend Setup
```bash
cd backend
npm install
node index.js
```

## 📱 Development

### Running the App
1Start the frontend: `cd frontend && npx expo start --lan`
2. Scan QR code with Expo Go app
3 backend (optional): `cd backend && node index.js`

### Adding New Screens
- Create files in `frontend/app/` following Expo Router conventions
- Use `(auth)/` for authentication screens
- Use `(tabs)/` for main app screens

## 🔧 Technologies

### Frontend
- **Expo** - Development platform
- **React Native** - Cross-platform mobile development
- **Expo Router** - File-based navigation
- **React Navigation** - Advanced navigation components
- **Firebase** - Authentication and Firestore

### Backend
- **Node.js** - Server runtime
- **Express** - Web framework
- **CORS** - Cross-origin resource sharing

## 📝 TODO
- [ ] Add Firebase project credentials
- [ ] Implement authentication flow
- [ ] Add more screens and features
- [ ] Set up protected routes
-Firestore database operations