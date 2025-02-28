# Medeasy App

## Overview
Medeasy is a mobile application designed to provide easy access to medicines, lab tests, supplements, and healthy food options. Built using **Kotlin**, the app follows the **MVVM architecture** and utilizes **Android Jetpack components** for a seamless user experience.

## Features
- Browse and purchase **medicines, lab tests, supplements, and healthy food**.
- Simple and user-friendly **home page** navigation.
- **Cart functionality** to manage selected products.
- Modern UI with **XML-based layouts**.
- Efficient performance using **Gradle** for dependency management.

## Technologies Used
- **Kotlin** – Main programming language.
- **Android Jetpack** – LiveData, ViewModel, Navigation Component.
- **Gradle** – Build automation.
- **XML** – UI design.
- **ProGuard** – Code optimization and obfuscation.

## Project Structure
```
├── build.gradle.kts
├── settings.gradle.kts
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── AndroidManifest.xml
│   │   │   ├── java/com/example/medeasy/
│   │   │   │   ├── MainActivity.kt
│   │   │   │   ├── HomePage.kt
│   │   │   │   ├── cart.kt
│   │   │   │   ├── MEDICINES.kt
│   │   │   │   ├── LAB_TEST.kt
│   │   │   │   ├── SUPPLEMENTS.kt
│   │   │   │   ├── HEALTHYFOOD.kt
│   │   │   │   ├── products.kt
│   │   │   ├── res/layout/
│   │   │   │   ├── activity_home_page.xml
│   │   │   │   ├── activity_cart.xml
│   │   │   │   ├── activity_medicines.xml
│   │   │   │   ├── activity_lab_test.xml
│   │   │   │   ├── activity_supplements.xml
│   │   │   │   ├── activity_healthyfood.xml
│   │   │   ├── res/values/
│   │   │   │   ├── colors.xml
│   │   │   │   ├── strings.xml
│   │   │   │   ├── themes.xml
```

## Installation
### Prerequisites
- **Android Studio** (latest version recommended)
- **Java JDK 8+**
- **Gradle**

### Steps
1. **Clone the repository**:
   ```bash
   git clone https://github.com/YOUR-USERNAME/sami-codeai-medeasyapp.git
   cd sami-codeai-medeasyapp
   ```
2. **Open in Android Studio**
3. **Sync Gradle** and install dependencies
4. **Run the app** on an emulator or physical device



