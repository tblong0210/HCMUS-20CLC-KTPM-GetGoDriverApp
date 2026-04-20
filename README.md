# GetGo Driver App 🚗

The dedicated mobile application for drivers on the GetGo platform, developed as part of the Software Engineering (KTPM) coursework at the University of Science (VNUHCM). This app allows drivers to receive ride requests, navigate to passengers, and manage their driver profiles.

## 🛠 Tech Stack

* **Framework:** React Native
* **Toolchain:** Expo (`expo-cli`)
* **State Management:** Redux Toolkit (`slices` and `store.js`)
* **Language:** JavaScript
* **Package Manager:** Yarn

## 📂 Project Structure

```text
HCMUS-20CLC-KTPM-GetGoDriverApp/
├── .expo/                  # Expo configuration folder
├── assets/                 # Local images, fonts, and icons
├── slices/                 # Redux Toolkit slices (state logic)
├── src/                    # Main source code (Components, Screens, Navigation)
├── App.js                  # Application entry point
├── app.json                # Expo manifest configuration
├── babel.config.js         # Babel transpiler configuration
├── package.json            # Project dependencies and scripts
├── store.js                # Redux store configuration
└── yarn.lock               # Dependency tree lockfile
```

## ✨ Features
*(Note: Update these based on your specific implementation)*
* **Driver Status:** Toggle online/offline availability to receive ride requests.
* **Ride Management:** Accept, decline, and track current rides.
* **State Management:** Predictable state updates using Redux for seamless app performance.

## 🚀 Getting Started

Follow these instructions to run the application on your local machine or a physical device.

### Prerequisites
* [Node.js](https://nodejs.org/) installed.
* [Yarn](https://yarnpkg.com/) installed globally.
* The **Expo Go** app installed on your physical iOS or Android device (or an emulator set up on your machine).

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/tblong0210/HCMUS-20CLC-KTPM-GetGoDriverApp.git
    cd HCMUS-20CLC-KTPM-GetGoDriverApp
    ```

2.  **Install dependencies:**
    It is recommended to use Yarn to ensure version consistency.
    ```bash
    yarn install
    ```

3.  **Start the Expo server:**
    ```bash
    yarn start
    # or npx expo start
    ```

4.  **Run the App:**
    * **On a physical device:** Scan the QR code displayed in the terminal using the Expo Go app (Android) or the default Camera app (iOS).
    * **On an emulator:** Press `a` in the terminal to open on Android, or `i` to open on an iOS simulator.
