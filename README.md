# Apex SMILE (System for Medical Information and Ledger Entry)
A comprehensive mobile application for managing patient data and practice operations. This application is built with React Native and integrates with Firebase for a license-based access control system. Patient data is intended to be stored locally for offline access.

---

### 🌟 Features

* **License Key Activation:** A secure, one-time activation process using a unique license key.
* **Device Management:** Each license key has a limit on the number of active devices.
* **Patient Management:** A placeholder for adding and managing patient records.
* **Offline First:** Designed to store patient data locally on the device, ensuring access even without an internet connection.

---

### 🛠️ Technology Stack

* **Framework:** React Native
* **State Management:** React Hooks (`useState`, `useEffect`)
* **Database & Authentication:** Firebase Firestore
* **Local Storage:** `@react-native-async-storage/async-storage`

---

### ⚙️ Installation & Setup

To run this app, you must have a local React Native development environment set up.

#### Prerequisites

* **Node.js:** Ensure you have the latest version of Node.js installed.
* **React Native CLI:** Install the command-line interface globally:
    ```bash
    npm install -g react-native-cli
    ```
* **JDK (Java Development Kit):** For Android development, make sure you have the JDK installed.
* **Android Studio or Xcode:** Set up either Android Studio (for Android) or Xcode (for iOS) with the required SDKs and simulators.

#### Project Setup

1.  **Create a new React Native project:**
    ```bash
    react-native init DentalApp
    ```

2.  **Navigate into the project directory:**
    ```bash
    cd DentalApp
    ```

3.  **Install the required dependencies:**
    ```bash
    npm install firebase @react-native-async-storage/async-storage
    ```

4.  **Configure Firebase:**
    * Go to the [Firebase Console](https://console.firebase.google.com/) and create a new project.
    * Add a new web app and copy your Firebase configuration object.
    * In the provided `App.js` code, replace the placeholder `firebaseConfig` with your own project's credentials.

5.  **Copy the code:**
    * Replace the contents of your `DentalApp/App.js` file with the full code provided in our conversation.

---

### 🚀 Usage

Once the setup is complete, you can run the application on your device or a simulator.

* **For Android:**
    ```bash
    react-native run-android
    ```
* **For iOS:**
    ```bash
    react-native run-ios
    ```

Upon the first launch, the app will prompt you to enter a license key. For testing purposes, you can use the following keys:

* **`VALID-KEY`**: Activates the app and proceeds to the main dashboard.
* **`LIMIT-REACHED`**: Simulates a license key that has reached its device activation limit.
* **Any other key**: Will be treated as an invalid key.

---

### 🤝 Contributing

Contributions are welcome! If you'd like to improve this project, please open a pull request.

---

### 📄 License

This project is licensed under the MIT License.
