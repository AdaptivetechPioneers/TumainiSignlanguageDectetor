
# Tumaini Flutter App

This project is a Flutter application that can be run on iOS, Android, and the web. Follow the steps below to get started with cloning and running the app on your local machine.
This project is an extension to help the deaf enjoy social media platforms like tiktok using an avatar to make them updated.
Below is a link of the pitch and demo
https://drive.google.com/drive/folders/1horY9Nr_5DjO6eSHCayaIdIdfj6RMCU2?usp=drive_link

## Table of Contents
- [Prerequisites](#prerequisites)
- [Clone the Repository](#clone-the-repository)
- [Setup Flutter](#setup-flutter)
- [Running the App](#running-the-app)
  - [Android](#android)
  - [iOS](#ios)
  - [Web](#web)
- [License](#license)

---

## Prerequisites

Before running the app, make sure you have the following installed:

1. **Flutter SDK**: Install Flutter by following the [official Flutter installation guide](https://flutter.dev/docs/get-started/install).
2. **IDE**: You can use any of the following editors:
    - [Android Studio](https://developer.android.com/studio)
    - [Visual Studio Code](https://code.visualstudio.com/) (with the Flutter and Dart extensions)
3. **Xcode** (for iOS development) [macOS only]: Install Xcode from the Mac App Store.
4. **Git**: Ensure you have Git installed to clone the repository. You can install it from [here](https://git-scm.com/).

## Clone the Repository

To get a copy of the project up and running, first clone the repository:


Navigate into the project directory:

```bash
cd your-flutter-app
```

## Setup Flutter

1. **Get Dependencies**: Run the following command to install the Flutter dependencies:

```bash
flutter pub get
```

2. **Connect to a Device/Emulator**: Ensure you have a physical device connected or an emulator running. You can check connected devices using:

```bash
flutter devices
```

3. **Check Flutter Setup**: Verify that your Flutter setup is correct:

```bash
flutter doctor
```

Make sure all checks are green, or follow the steps given by `flutter doctor` to fix any issues.

## Running the App

### Android

1. **Set Up Android Device or Emulator**: Use Android Studio or AVD Manager to launch an emulator, or connect a physical Android device.
2. **Build and Run**: Execute the following command to run the app on Android:

```bash
flutter run
```

### iOS

1. **Set Up iOS Device or Simulator**: Open Xcode and create a simulator or connect an iOS device.
2. **Run the App**: Use this command to run the app on iOS:

```bash
flutter run
```

> **Note**: Ensure you have the necessary code signing configurations in Xcode to deploy the app on a real device.

### Web

1. **Ensure a Web Browser is Installed**: You can run the Flutter app in Chrome or any other web browser.
2. **Run on Web**:

```bash
flutter run -d chrome
```



This should serve as a clear and concise README to help users clone and run your Flutter app. Let me know if you'd like to adjust or add anything specific!