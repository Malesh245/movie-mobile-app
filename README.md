Mobile Movie App

Introduction

Welcome to the Mobile Movie App! This application, built using Expo React Native, provides users with a seamless experience to explore a vast collection of movies. Users can browse movies by genre, search for specific titles, and view detailed information, including ratings, reviews, and trailers. Whether you're a movie enthusiast or just looking for your next watch, this app has you covered!

Features

🎬 Browse Movies by Genre – Discover movies from different categories.

🔍 Search for Specific Titles – Find your favorite movies instantly.

📝 View Movie Details – Get information on ratings, reviews, and trailers.

🎥 Watch Trailers – View official trailers before deciding what to watch.

📱 User-Friendly Interface – Enjoy a smooth and intuitive UI.

Installation

Follow these steps to set up and run the Mobile Movie App:

Prerequisites

Node.js installed on your system

Expo CLI installed globally (npm install -g expo-cli)

A mobile device with the Expo Go app installed (iOS/Android) or an emulator

Steps to Install

Clone the repository:

git clone https://github.com/yourusername/mobile_movie_app.git

Navigate to the project directory:

cd mobile_movie_app

Install dependencies:

npm install

Environment Variables

To run the Mobile Movie App, you need to set up the following environment variables in a .env file:

EXPO_PUBLIC_MOVIE_API_KEY=your_movie_api_key_here
EXPO_PUBLIC_APPWRITE_PROJECT_ID=your_project_id_here
EXPO_PUBLIC_APPWRITE_DATABASE_ID=your_database_id_here
EXPO_PUBLIC_APPWRITE_COLLECTION_ID=your_collection_id_here

Where to Get These Keys?

EXPO_PUBLIC_MOVIE_API_KEY: Obtain it from The Movie Database API

EXPO_PUBLIC_APPWRITE_PROJECT_ID: Found in your Appwrite console under project settings

EXPO_PUBLIC_APPWRITE_DATABASE_ID: Located in the Appwrite database section

EXPO_PUBLIC_APPWRITE_COLLECTION_ID: Available under the collection settings in Appwrite

Usage

To run the application:

Start the development server:

npm start

Scan the QR code in your terminal using the Expo Go app (iOS/Android) OR press w to open the app in a web browser.

Running on an Emulator or Physical Device

Android Emulator: Run npx expo run:android

iOS Simulator: Run npx expo run:ios (macOS required)

Physical Device: Open the Expo Go app and scan the QR code displayed in the terminal.

Contributing

We welcome contributions! If you’d like to improve this project, please follow these steps:

Fork the repository

Create a new branch (feature-branch)

Make your changes

Commit your changes (git commit -m "Add new feature")

Push to the branch (git push origin feature-branch)

Create a Pull Request

Please read our CONTRIBUTING.md for more details.

License

This project is licensed under the MIT License. See the LICENSE file for more information.

Contact

For any inquiries, feel free to reach out:
📧 Email: your.email@example.com

Happy Coding! 🚀

