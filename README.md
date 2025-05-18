# Google-keep-clone# Google Keep Clone with React & Firebase

A feature-rich notes application with real-time syncing, offline support, and tag management.

![App Screenshot](screenshots/app-preview.png)

## Features

- **Real-time Syncing**: Instant updates across devices using Firebase Firestore
- **Offline Support**: Full CRUD functionality works without internet connection
- **Tag System**: Organize notes with customizable tags
- **Color Coding**: Color palette for visual organization
- **Search**: Find notes instantly with full-text search
- **Authentication**: Secure user accounts with Firebase Auth

## Technologies

- **Frontend**: React (with Hooks & Context API)
- **Backend**: Firebase (Firestore, Authentication)
- **State Management**: React Context API
- **Offline Support**: Service Workers, IndexedDB
- **Styling**: CSS Modules

## Performance

- **First Contentful Paint**: <1.5s
- **Offline Cache**: Stores up to 500 notes locally
- **Sync Speed**: Updates propagate in <500ms

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Manaswini-wq/google-keep-clone.git
   cd google-keep-clone
