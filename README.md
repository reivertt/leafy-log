# 🌿 Leafy Log

Leafy Log is a Flutter mobile app for keeping track of your houseplants. Register your plants, log their care history, schedule recurring tasks with reminders, and look up species in a built-in plant encyclopedia.

Built as the final project for the Mobile Programming course.

## ✨ Features

- **Authentication**: register, log in, edit your profile, and reset your password with Firebase Authentication.
- **Plant management**: add, view, edit, and delete your own plants.
- **Care logs**: record watering, fertilizing, and other maintenance for each plant to keep a history of its care.
- **Scheduled tasks and notifications**: create tasks for a plant and get notified when they are due.
- **Plant encyclopedia**: search plant species through an external API and add new plants to the encyclopedia.

## 🛠️ Tech Stack

- [Flutter](https://flutter.dev) (Dart SDK ^3.7.0)
- [Firebase Authentication](https://firebase.google.com/docs/auth) and [Cloud Firestore](https://firebase.google.com/docs/firestore) for accounts and data
- [GetX](https://pub.dev/packages/get) for state management and navigation
- [awesome_notifications](https://pub.dev/packages/awesome_notifications) for task reminders
- [http](https://pub.dev/packages/http) and [flutter_dotenv](https://pub.dev/packages/flutter_dotenv) for the encyclopedia API and configuration

## 🚀 Getting Started

### 📋 Prerequisites

- Flutter SDK (Dart ^3.7.0)
- A Firebase project with Authentication and Firestore enabled
- An API key for the plant encyclopedia service

### ⚙️ Setup

1. Clone the repository and install dependencies:
   ```bash
   git clone https://github.com/reivertt/leafy-log.git
   cd leafy-log
   flutter pub get
   ```
2. Connect the app to your Firebase project (for example with `flutterfire configure`).
3. Create a `.env` file in the project root and add your API key and any other settings the app reads from it.
4. Run the app:
   ```bash
   flutter run
   ```

## 📸 Screenshots

### 🔐 Login & Register
<p float="left">
  <img src="https://github.com/user-attachments/assets/b73a53ea-6b19-4ca3-b061-88fffa72ecee" width="300" />
  <img src="https://github.com/user-attachments/assets/b355d738-beae-4186-b054-87e0fba92a01" width="300" />
</p>

### 🏠 Home Screen
<img src="https://github.com/user-attachments/assets/21f10b74-5771-4eaa-b5a5-0ce840a23c2c" alt="Home Screen" width="300"/>

### 🪴 Plant Screen
<img src="https://github.com/user-attachments/assets/ed347971-6e45-45a1-bd09-9b591dc53011" alt="Plant Screen" width="300"/>

### 🔍 Plant Detail
<img src="https://github.com/user-attachments/assets/5a3861db-27e2-4322-afa1-3fff4971a024" alt="Plant Detail 1" width="300"/>
<img src="https://github.com/user-attachments/assets/34d35736-7163-4dbd-b7fc-0bee59ce436b" alt="Plant Detail 2" width="300"/>

<p float="left">
  <img src="https://github.com/user-attachments/assets/1a2a40fc-932d-4430-9e6a-24a1b8fd8b4e" alt="Plant Detail 3" width="300"/>
  <img src="https://github.com/user-attachments/assets/7c7f54b6-a865-45db-8c20-0788d8d42575" alt="Plant Detail 4" width="300"/>
</p>

<p float="left">
  <img src="https://github.com/user-attachments/assets/73915d53-6522-4007-a14b-2fc1fe29d059" alt="Plant Detail 5" width="300"/>
  <img src="https://github.com/user-attachments/assets/297e38ba-54c1-4c34-a41e-c7cfbfd5a0be" alt="Plant Detail 6" width="300"/>
</p>

### ⏰ Schedule Screen
<img src="https://github.com/user-attachments/assets/f0249a5f-f90b-443d-b143-9067edfa1156" alt="Schedule" width="300"/>

### 📖 Encyclopedia Screen
<img src="https://github.com/user-attachments/assets/914bee20-49bd-4423-930f-d608117724ba" alt="Encyclopedia 1" width="300"/>
<img src="https://github.com/user-attachments/assets/7b2d2ec8-4c81-4904-a97a-53d48c4d9586" alt="Encyclopedia 2" width="300"/>

## 👥 Authors

- Duevano Fairuz Pandya (5025211052)
- Muhammad Nabil Akhtar Raya Amoriza (5025221021)
- Fauzan Dzikri Rabbani (5025221311)
