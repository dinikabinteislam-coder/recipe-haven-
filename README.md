# Recipe Haven - NIT3213 Final Assignment

## Project Overview
This Android application was developed for the NIT3213 Final Assignment. It demonstrates proficiency in API integration, user interface design, and modern Android development best practices. The app interacts with the `vu-nit3213-api` to authenticate users and display a list of recipes via a Dashboard and a detailed view.

## Features
* **Login Screen:** Authenticates users via a POST request using the student's first name as the username and the student ID as the password.
* **Dashboard Screen:** Displays a summary list of items retrieved via a GET request using a modern `RecyclerView`.
* **Details Screen:** Displays the complete description and properties of a selected entity.

## Technical Stack & Architecture
* **Language:** Kotlin
* **Architecture:** MVVM (Model-View-ViewModel) and Clean Code principles.
* **UI:** Android XML with ViewBinding.
* **Navigation:** Android Navigation Component (SafeArgs).
* **Dependency Injection:** Dagger Hilt[cite: 1].
* **Networking:** Retrofit2 & OkHttp3.
* **Asynchronous Programming:** Kotlin Coroutines.

## Dependencies
The following major dependencies are used in this project[cite: 1]:
* `com.google.dagger:hilt-android:2.48` - Dependency Injection framework[cite: 1].
* `com.squareup.retrofit2:retrofit:2.9.0` - Type-safe HTTP client for API requests.
* `com.squareup.retrofit2:converter-gson:2.9.0` - JSON parsing.
* `androidx.navigation:navigation-fragment-ktx:2.7.7` - In-app navigation.
* `androidx.lifecycle:lifecycle-viewmodel-ktx:2.7.0` - ViewModel lifecycle management.

## Prerequisites
To build and run this application, you will need:
* Android Studio (Jellyfish or newer recommended).
* Minimum SDK: API 24 (Android 7.0).
* Target SDK: API 34 (Android 14).
* An active internet connection (for API requests).

## Setup Instructions
1. **Clone the repository:**
```bash
   git clone [https://github.com/YourUsername/YourRepositoryName.git](https://github.com/YourUsername/YourRepositoryName.git)
Open the project:

Launch Android Studio.

Select File > Open and navigate to the cloned repository folder.

Sync Project with Gradle Files:

Android Studio should automatically sync the project. If not, click the "Sync Project with Gradle Files" icon in the top toolbar to download all required dependencies[cite: 1].

How to Build and Run the Application
Connect a Device:

Connect a physical Android device via USB (with USB Debugging enabled) OR start an Android Virtual Device (Emulator) from the Device Manager[cite: 1].

Run the App:

Click the green Run 'app' (Play) button in the top toolbar of Android Studio, or press Shift + F10[cite: 1].

Using the App:

Login: Enter the assigned credentials.

Username: Dinika[cite: 1]

Password: s8145621[cite: 1]

Wait for the authentication to process. Upon success, you will be routed to the Dashboard[cite: 1].

Tap on any item in the Dashboard to view its full details[cite: 1].

Author
Name: Dinika Binta Islam

Student ID: s8145621