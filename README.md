# 📚 StudyNest

StudyNest is a comprehensive Android application designed to be a one-stop solution for students, helping them organize their study schedule, manage time effectively, store notes, and stay productive using smart tools like the Pomodoro timer and push notifications.

---

## 👥 Team Members

- Emilio Govender – ST10381731  
- Deshalin Naicker – ST10287087  
- Ethan Anthoo – ST10269386  
- Denell Vandayar – ST10373357  

---

## 📹 YouTube Demo
[Watch Demo](#) <!-- Add actual link -->

## 🧩 API GitHub
[StudyNest API](https://github.com/DenellVandayar/StudyNestApi.git)

---

## 🚀 Key Features

### 🔐 User Authentication
- Secure sign-up and login via email and password  
- Google SSO integration  
- Biometric Authentication (Fingerprint) for seamless quick login  
- Powered by Firebase Authentication  

### ⏱️ Pomodoro Timer
- Three preset study modes:
  - Pomodoro (25 minutes)  
  - Short Break (5 minutes)  
  - Long Break (30 minutes)  
- Start/Stop anytime  
- Custom vibration and sound settings  
- Helps improve productivity and focus  

### 🗒️ Notes Management
Users can:
- Create notes  
- View notes  
- Edit notes  
- Delete notes  
All stored securely and synced across sessions.

### 🗓️ Study Planner
- Visual calendar at the top  
- List of important study dates added by the user  
- Easy date overview for exam planning and assignment tracking  

### 🎨 Customizable Themes
- Users can pick their preferred theme color  
- Light/dark style adjustments  
- Timer vibration and sound toggles in settings  

---

## 🆕 NEW Features Added

### 🧬 1. Biometric Authentication
- Integrated BiometricPrompt API to allow fingerprint/biometric login  
- Provides faster and more secure app access  

### 🔌 2. Offline Sync Mode
- Offline-first data system allowing users to:
  - Access and create notes  
  - Use the timer  
  - View/add calendar dates even without internet  
- Automatic sync with backend when internet is restored  

### 🔔 3. Push Notifications (Firebase Cloud Messaging)
- Real-time notifications for:
  - Upcoming study session dates (10-minute reminders)  
- Tracks scheduled dates  
- Integrated using Firebase Cloud Messaging (FCM)  

### 🌍 4. Multi-Language Support
- Supports English, isiZulu, and Afrikaans  
- Languages switch automatically based on device settings or manually in-app  

---

## 📄 Release Notes – StudyNest (Final Release)

### ✅ New Features Added Since the Prototype
1. **Biometric Authentication**
   - Secure fingerprint login  
   - Works with Firebase Authentication and Google Sign-In  

2. **Offline Mode with Automatic Sync**
   - Offline-first storage with Room Database  
   - Syncs automatically with cloud when back online  

3. **Push Notifications for Real-Time Updates**
   - Firebase Cloud Messaging for reminders and alerts  
   - Notifications received even when the app is closed  

4. **Multi-Language Support**
   - In-app language switching  
   - English, isiZulu, Afrikaans  

### 🔄 Improvements to Existing Prototype Features
5. **Enhanced Pomodoro Timer**
   - Improved UI and reliability  
   - Vibration/sound toggles  
   - Continues after screen rotation  

6. **Notes Feature Upgraded**
   - Improved editor UI  
   - Offline saving with delayed cloud sync  
   - Faster loading and smoother edit/delete animations  

7. **Study Planner Enhancements**
   - Redesigned calendar for better layout  
   - Cleaner upcoming study sessions list  

8. **Settings Page Improvements**
   - Language selector  
   - Theme color customization  
   - Biometric on/off toggle  
   - Notification preferences (sound/vibration)  

### 🛠️ Bug Fixes & Stability Improvements
- Fixed crashes on login screen  
- Fixed navigation errors  
- Improved API communication and error handling  
- Reduced loading times  
- Consistent layout across devices  

---

## ⭐ Summary
This release introduces four major innovative features: **biometrics, offline mode, push notifications, and multilingual support**, while improving the original functionality for a smoother, more reliable user experience.

---

## 🧩 Dependencies
- Android Studio Iguana | 2023.2.1 or later  
- Android device/emulator running API 26+  
- Firebase Authentication  
- Firebase Cloud Messaging  
- Retrofit / RoomDB (for API + offline storage)  

---

## 🛠️ Installation
```bash
Clone the repository: git clone [https://github.com/your_username/StudyNest.git](https://github.com/VCWVL/prog7314-poe-ST10381731.git)
```
1. Open the project in Android Studio.

2. Sync the Gradle files by clicking the "Sync Now" button that appears in the top bar.

3. Run the app on your selected device or emulator.

🧾 Plagiarism Declaration

We hereby declare that the contents of this project, including all code and documentation, is our own original work except where explicitly referenced.

We confirm:

No part of this project was copied without acknowledgment

Only assistance used: Google Gemini Code Assist and ChatGPT, strictly for:

Syntax suggestions

Improving code readability

Generating comments

Improving productivity

We take full responsibility for all logic, structure, and functionality of the codebase.
