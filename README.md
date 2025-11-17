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

*(Add link here)*

## 🧩 API GitHub

[https://github.com/DenellVandayar/StudyNestApi.git](https://github.com/DenellVandayar/StudyNestApi.git)

---

## 🚀 Key Features

### 🔐 User Authentication

- Secure sign-up and login via email and password  
- Google SSO integration  
- Biometric Authentication (Fingerprint) added for seamless quick login  
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

- A visual calendar at the top  
- List of important study dates added by the user  
- Easy date overview for exam planning and assignment tracking  

### 🎨 Customizable Themes

- Users can pick their preferred theme color  
- Light/dark style adjustments  
- Timer vibration and sound toggles in settings  

---

## 🆕 NEW Features Added

### 🧬 1. Biometric Authentication

Integrated BiometricPrompt API to allow:  
- Fingerprint login  
- Fingerprint/biometric login (supported)  

This provides faster and more secure app access.

### 🔌 2. Offline Sync Mode

Designed an offline-first data system allowing users to:  
- Access and create notes  
- Use the timer  
- View/add calendar dates even when there is no internet connection  

When internet returns:  
- All offline data automatically syncs with the backend API  

### 🔔 3. Push Notifications (Firebase Cloud Messaging)

Users receive real-time notifications for:  
- When approaching study session dates set by the user a important study reminder goes off usually 10 minutes before the date set  

These reminders are received in real time.  
- Tracks Scheduled dates  
- Integrated using Firebase Cloud Messaging (FCM)  

### 🌍 4. Multi-Language Support

StudyNest now supports multiple languages, including:  
- English  
- isiZulu  
- Afrikaans  

Languages automatically switch based on device settings or can be changed manually inside the app.  

This version of the StudyNest App now includes:  
- Biometrics  
- Offline sync  
- Push notifications  
- Multi-language support  

---

## Release Notes – StudyNest (Final Release)

Below is a summary of all updates and improvements that have been made to StudyNest since the original prototype. This release focuses on enhancing security, accessibility, reliability, and overall user experience.

### ✅ New Features Added Since the Prototype

1. **Biometric Authentication (NEW – Innovative Feature)**  
   - Added secure fingerprint authentication using Android’s BiometricPrompt API  
   - Users can now log in instantly without entering email/password  
   - Works together with existing Firebase Authentication and Google Sign-In  

2. **Offline Mode with Automatic Sync (NEW – Innovative Feature)**  
   - Implemented offline-first storage using Room Database  
   - Users can create, edit, and delete notes or study dates even with no internet connection  
   - When the device reconnects, all changes sync with the cloud automatically  
   - Greatly improves reliability for users in low-connectivity environments  

3. **Push Notifications for Real-Time Updates (NEW – Innovative Feature)**  
   - Added Firebase Cloud Messaging to send reminders, alerts, and study-related notifications  
   - Users receive notification updates even when the app is closed  
   - Supports scheduled study reminders and timer start updates  

4. **Multi-Language Support (NEW – Innovative Feature)**  
   - Added full in-app language switching  
   - Supports English, isiZulu, and Afrikaans, making the app more inclusive for South African users  
   - All UI labels, buttons, and key pages are translated  

### 🔄 Improvements to Existing Prototype Features

5. **Enhanced Pomodoro Timer**  
   - Improved UI for the Pomodoro, Short Break, and Long Break timers  
   - Added vibration/sound toggle for alerts  
   - Added reliability fixes so timers continue working even after screen rotation  

6. **Notes Feature Upgraded**  
   - Improved notes editor UI  
   - Added offline saving and delayed cloud sync  
   - Faster loading and improved delete/edit animations  

7. **Study Planner Enhancements**  
   - Calendar redesigned for better layout and usability  
   - Upcoming study sessions now appear in a cleaner list view  

8. **Settings Page Improvements**  
   - Added language selector  
   - Added theme color customization  
   - Added biometric on/off toggle  
   - Added notification preference controls (sound/vibration)  

### 🛠️ Bug Fixes & Stability Improvements

- Fixed crashes on login screen  
- Fixed navigation errors when switching between pages  
- Improved API communication and error handling  
- Reduced loading times throughout the app  
- Improved layout spacing and consistency across devices  

### ⭐ Summary

This release represents a significant upgrade over the prototype, introducing four major innovative features—biometrics, offline mode, push notifications, and multilingual support—while improving the original functionality and ensuring a smoother, more reliable user experience.  

---

## 🧩 Dependencies

To run the project you will need:  
- Android Studio Iguana | 2023.2.1 or later  
- Android device/emulator running API 26+  
- Firebase Authentication  
- Firebase Cloud Messaging  
- Retrofit / RoomDB (for API + offline storage)  

---

## 🛠️ Installation

```bash
git clone https://github.com/your_username/StudyNest.git(https://github.com/VCWVL/prog7314-poe-ST10381731.git)
```
1. Open the project in Android Studio.

2. Sync the Gradle files by clicking the "Sync Now" button that appears in the top bar.

3. Run the app on your selected device or emulator.

## 🧾 Plagiarism Declaration

We hereby declare that the contents of this project, including all code and documentation, is our own original work except where explicitly referenced.

We confirm:

No part of this project was copied without acknowledgment

Only assistance used: Google Gemini Code Assist and ChatGPT, strictly for:

Syntax suggestions

Improving code readability

Generating comments

Improving productivity

We take full responsibility for all logic, structure, and functionality of the codebase.
