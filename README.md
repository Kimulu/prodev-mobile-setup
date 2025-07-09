# 📱 Mobile Development Setup & First App with Expo

This document covers the setup of a mobile development environment using Expo and the creation of your first React Native app using the Expo Router template.

---

## ✅ Environment Setup

### Tools Installed

- **Node.js LTS** ✅
- **Visual Studio Code** ✅
- **Compatible OS**: Windows ✅
- **Expo Go on Android** ✅

### Expo Go Setup

1. Installed **Expo Go** from the [Google Play Store](https://expo.dev/go).
2. Logged into an existing Expo account successfully.
3. Confirmed Expo Go runs properly and is ready to preview QR code builds.

---

## 🚀 Creating Your First Mobile App with Expo Router

### 🔧 Steps Followed

1. Opened terminal and navigated to the project directory:
   ``
   cd prodev-mobile-setup
   Initialized a new Expo project using the latest Expo Router template:

npx create-expo-app@latest .
Opened the file:

app/(tabs)/index.tsx
Modified the default text:

tsx

// Original:
Welcome!

// Updated:
** First App Created **
Started the development server:

npx expo start
Used the Expo Go app to scan the QR code and run the app on an Android device.

🔄 Resetting the Application
Ran the reset command to clear project state:

npm run reset-project
📝 Observations:
After resetting, the project was refreshed.

A new directory named app-example was automatically created.

Inside this folder:

app-example/app/(tabs)/index.tsx (contains a default screen)

app-example/constants/Colors.tsx

It appears that app-example acts as a fallback demo or backup template after reset.

🛠️ Challenges Faced
✅ No issues during setup or project initialization.

❗ The creation of the app-example folder after reset was unexpected but did not affect the main app.

📂 Directory Structure (Post Reset)

prodev-mobile-setup/
│
├── app/ # Main project files
│ └── (tabs)/index.tsx # Modified to show "** First App Created **"
│
├── app-example/ # Created after reset
│ ├── app/(tabs)/index.tsx
│ └── constants/Colors.tsx
│
├── README.md # This file
✅ Status
Mobile development environment is fully set up and tested. First app created, customized, and verified on a physical Android device using Expo Go.
