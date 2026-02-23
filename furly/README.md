🐾 Furly – Trusted Pet Care Mobile App
Furly is a Flutter-based mobile application designed to help urban pet owners find trusted caregivers and stay updated about their pet’s wellbeing in real time.

Built using Flutter + Firebase, Furly provides secure authentication, real-time booking management, and cloud-backed data synchronization.

📌 Problem Statement
Pet owners in cities often struggle to find trustworthy walkers or caregivers. Existing solutions lack proper identity verification and real-time updates, leading to anxiety about pet safety.

Furly solves this by providing a trusted discovery and monitoring system powered by Firebase.

🎯 Project Objective
To build a mobile-first MVP that:

Enables secure user authentication

Allows caregivers to create profiles

Lets pet owners book caregivers

Provides real-time booking status updates

Demonstrates strong Flutter–Firebase integration

🛠 Tech Stack
Frontend

Flutter (Dart)

Backend (BaaS)

Firebase Authentication

Cloud Firestore

Firebase Core

Tools

GitHub

Android Studio / VS Code

FlutterFire CLI

🔥 Firebase Integration
Firebase Services Used
🔐 Authentication
Email & Password Sign Up / Login

Persistent user sessions

☁️ Cloud Firestore
Stores:

User profiles

Caregiver data

Booking details

Real-time synchronization across devices

📱 Core Features (MVP)
User Registration & Login

Caregiver Profile Creation

Pet Owner Dashboard

Booking Request Flow

Requested

Accepted

Completed

Real-time data updates using StreamBuilder

Working Android APK build

🏗 App Architecture
Flutter follows a widget-based reactive architecture:

StatelessWidget → Static UI components

StatefulWidget → Dynamic UI components

setState() → Triggers UI rebuild

Firebase streams → Real-time updates

🔄 How Real-Time Sync Works
Cloud Firestore uses streams:

Data is written to Firestore

Firestore pushes updates to connected clients

Flutter rebuilds only affected widgets

UI updates instantly without manual refresh

This ensures seamless user experience.

🚀 Getting Started
1️⃣ Clone the Repository
git clone <your-repo-link>
cd furly
2️⃣ Install Dependencies
flutter pub get
3️⃣ Add Firebase Configuration
Download google-services.json from Firebase Console and place it in:

android/app/google-services.json
4️⃣ Run the App
flutter run
📂 Project Structure
lib/
 ├── main.dart
 ├── screens/
 ├── widgets/
 ├── services/
📊 Functional Requirements
Users can register and login securely

Caregivers can create and update profiles

Owners can create and manage bookings

Data updates in real time

User sessions persist across restarts

⚡ Non-Functional Requirements
Responsive UI

Secure Firebase rules

Real-time performance

Scalable backend (Firebase-managed)


📈 Future Enhancements
Live GPS tracking

Push notifications

Ratings & reviews

Payment integration

Admin verification system

💡 Key Learnings
Flutter’s reactive widget system simplifies UI development

Firebase eliminates backend infrastructure complexity

Real-time streams improve user experience significantly

Cross-platform development is faster with a single codebase

👨‍💻 Developed By
Hrishob Pal & Sreenija
Sprint #2 – Flutter & Firebase Project

