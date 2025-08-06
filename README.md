# 📱 ChatApplication (Android - Java + Firebase)

An internal chat application designed specifically for company employees to communicate and share updates within their teams. It supports one‑on‑one messaging, group chats, and real‑time updates, fostering team collaboration and streamlined internal communication.

---

## 🚀 Features

- 🔐 Employee authentication via Firebase Authentication  
- 💬 One‑to‑one and group chat with real‑time messaging (Firebase Firestore)  
- 📎 Support for sending images and attachments (Firebase Storage)  
- 🔔 Push notifications using Firebase Cloud Messaging  
- 🧑‍🤝‍🧑 Role-based chat groups (e.g., team-wise)  
- 📁 Well-organized package structure for Activities, Models, Adapters, Firebase helpers, and Utilities

---

## 📂 Project Structure

app/
├── src/main/java/com/yourcompany/chatapplication/
│ ├── activities/ # Activity classes (Chat, Login, Profile, etc.)
│ ├── models/ # Data model classes (User, Message)
│ ├── adapters/ # RecyclerView adapters for chat UI
│ ├── firebase/ # Firebase helper methods (Auth, Firestore, Storage)
│ └── utils/ # Utility classes (e.g., SharedPrefs, Constants)
├── res/
│ ├── layout/ # XML layout files
│ ├── drawable/ # App icons and graphics
│ └── values/ # Colors, styles, strings


---

## 🛠 Prerequisites

- Android Studio (latest stable version)  
- Android SDK (API 21+)  
- A Firebase project with:
  - Authentication (Email/Password)
  - Firestore Database
  - Firebase Storage
  - Firebase Cloud Messaging (FCM)

---
