# Todo App (SwiftUI + Firebase)

A simple Todo list iOS app built with SwiftUI for the Mobile Computing Lab.

## Features
- Register and Login with email and password (Firebase Authentication)
- Each task has a title and a description
- Create, read, update and delete tasks (CRUD)
- Tasks are stored per user in Cloud Firestore (`users/{uid}/tasks`)
- Mark tasks as done

## Tech stack
- SwiftUI
- Firebase iOS SDK 9.6.0 (Swift Package Manager): Firestore
- Firebase Authentication (REST API)

## How to run
1. Open `To-do-app-2207076.xcodeproj` in Xcode.
2. Create a Firebase project and add an iOS app with bundle ID `abc.To-do-app-2207076`.
3. Enable **Authentication > Email/Password** and create a **Firestore Database**.
4. Download `GoogleService-Info.plist` and add it to the `To-do-app-2207076` folder (check the app target).
5. Select an iPhone simulator and press Run.

Note: `GoogleService-Info.plist` is not included in this repository.
