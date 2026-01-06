# FINDX - AI-Powered Lost & Found Platform

## Environment Setup

Create a `.env.local` file in the root folder with these variables:

```
# Firebase Configuration
NEXT_PUBLIC_FIREBASE_API_KEY="AIzaSyDO_rra0LWfDEMt6YPMxyiOIC00TCl7mas"
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN="codequest-hub.firebaseapp.com"
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=1:1045697943794:web:8bf2d46e9ff0e0dee6986b

# Gemini AI API Key
NEXT_PUBLIC_GEMINI_API_KEY=your_gemini_api_key
```

## Getting Started

1. Install dependencies:
```bash
npm install
```

2. Run the development server:
```bash
npm run dev
```

3. Open [http://localhost:3000](http://localhost:3000)

## Features

- 🤖 AI-powered image analysis with Google Gemini
- 🎤 Voice input with speech recognition
- 📱 PWA support (installable, offline-capable)
- 🔔 Push notifications
- 🦸 Hero gamification system
- 🗺️ Location-based matching
- 🔒 Verification questions for secure claims

## Tech Stack

- Next.js 14 (App Router)
- TypeScript
- Tailwind CSS
- Firebase (Auth, Firestore, Storage)
- Google Gemini AI
- Framer Motion
