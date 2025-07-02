# ChurchApp – Live Translation for Church Services 

**ChurchApp** is a **Flutter-based mobile application** designed for **live translation services in church settings**.  
The app enables users to **log in securely, access real-time translations, and connect to Bluetooth translation devices**.  
It supports multiple languages and offers a **modern, user-friendly UI** with **Material & Cupertino widgets**.

---

##  Features
✅ **Login Authentication** – Secure access with password validation.  
✅ **Live Translation** – Select from **English, Chinese, Vietnamese, and Spanish** for real-time translation.  
✅ **Bluetooth Connectivity** – Easily pair with **translation devices** for seamless audio transmission.  
✅ **Cross-Platform Support** – Works on **Android, iOS, and Windows** with Flutter.  
✅ **Modern UI** – Uses **Material & Cupertino widgets** for an intuitive interface.  

---

##  Technologies Used
- **Flutter (Dart)**
- **Firebase Authentication** (for secure login)
- **Bluetooth API** (for device connectivity)
- **WebSockets** (for live translation streaming)
- **SQLite** (for offline user data storage)

---

##  Getting Started

1️.  **Clone the Repository**
git clone https://github.com/Duncan1738/church-translation-app-locally-.git
cd churchapp
2️.  Install Flutter & Dependencies
Ensure Flutter is installed on your system. Then, install required dependencies:
flutter pub get
3️. Run the App on an Emulator or Device
flutter run

---
### Screenshots
Login Screen	Live Translation	Bluetooth Pairing
**Project Structure**
- 📂 churchapp/
- │── 📂 lib/                 # Main Flutter app files
- │   │── 📂 screens/         # UI Screens (Login, Translation, Settings)
- │   │── 📂 services/        # Authentication & Bluetooth services
- │   │── 📂 models/          # Data models for users & translations
- │   │── 📂 widgets/         # Reusable UI components
- │   │── main.dart           # Main application entry point
- │── 📂 assets/              # App assets (icons, images)
- │── pubspec.yaml            # Flutter dependencies
- │── README.md               # Documentation

---
### How It Works
1️. User Logs In – Secure authentication using Firebase.
2️. Selects a Language – Choose English, Chinese, Vietnamese, or Spanish.
3️. Connects via Bluetooth – Pair with translation device.
4️. Receives Live Translations – Text/audio streaming for real-time translation.

---
MIT licence
