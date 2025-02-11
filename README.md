# SatStay

A Bitcoin-only platform for short-term rentals, focusing on privacy, simplicity, and community.

## Features

- **User Authentication** - Secure sign-up and login using email and password.
- **Create and Manage Listings** - Hosts can create listings with essential details.
- **Browse Listings** - Guests can explore available rentals.
- **Booking System** - Basic request system for booking a stay.
- **User Profiles** - Manage your profile, including your Bitcoin wallet address for transactions.

## Project Status

- **MVP**: In development. Goals include:
  - Basic user authentication.
  - Simple listing creation and management.
  - A minimal booking request system.

## Getting Started

### Prerequisites

- Node.js (LTS version recommended)
- React Native CLI
- Firebase CLI (for Firebase setup)

### Installation

1. **Clone the repo:**
   ```sh
   git clone https://github.com/joshuambogart/SatStay.git
   cd SatStay

2. **Install dependencies:**
    for backend
    ```sh
    cd backend
    npm install

    for frontend
    ```sh
    cd frontend/SatStayApp
    npm install

3. **Firebase Configuration:**

    -Create a Firebase project.
    -Add your google-services.json (Android) and GoogleService-Info.plist (iOS) to the respective directories.
    -Set up Firebase Admin SDK for backend.

**Run the app:**
    Backend:
    ```sh
    cd backend
    npm start
    Frontend:
    ```sh
    cd frontend/SatStayApp
    npx react-native run-ios  # or run-android

**Usage**
    -Follow the on-screen prompts for user authentication.
    -Navigate through the app to create listings or make booking requests.

**Contributing**
For details on how you can contribute, please see our [Contributing Guidelines](CONTRIBUTING.md).

This project is licensed under the MIT License - see the LICENSE.md file for details

**Acknowledgments**
    Hat tip to anyone whose code was used
    Inspiration etc

**Project Management**
    We use GitHub Projects for managing tasks and features. Check out our Project Board for current and upcoming work.