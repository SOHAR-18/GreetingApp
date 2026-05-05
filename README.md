# GreetingApp

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

A modern, lightweight Android application built with Kotlin and Jetpack Compose that demonstrates a friendly "greeting" experience. Designed as a demo/tutorial app and a foundation for building a feature-rich greeting/communication app.

Table of contents
- Overview
- Features
- Tech stack
- Screenshots
- Getting started (setup & installation)
- How it works — demonstration / example
- Project structure
- Build, test & release
- CI / automation (suggested)
- Contributing
- Roadmap
- License
- Credits & contact

---

## Overview

GreetingApp is a simple and elegant Android application that showcases modern Android development practices:
- Kotlin-first codebase
- UI built with Jetpack Compose (Material 3)
- Clean, testable modules and Compose previews
- Gradle Kotlin DSL for builds

It is ideal as a learning project, demo, or starting point for a production-ready messaging/greeting feature.

---

## Features

- Minimal and intuitive UI with Compose
- Input a name/message and show a personalized greeting
- Material 3 theming with light/dark modes
- Small, focused codebase to demonstrate Compose patterns
- Unit and UI test setup for reliable development

---

## Tech stack

Core
- Kotlin (primary language)
- Jetpack Compose (UI toolkit)
- AndroidX libraries (Activity, Lifecycle, Core KTX)
- Material 3 (Compose Material components)
- Gradle (Kotlin DSL)

Build & Tooling
- Gradle (Kotlin DSL: build.gradle.kts)
- JDK 11+
- Android Studio (recommended latest stable)
- Version catalog via libs.versions.toml

Testing
- JUnit (unit tests)
- Espresso + Compose UI Test utilities (instrumented tests)

Repository language composition: Kotlin (~100%).

---

## Screenshots

Replace the placeholders below with real screenshots (place the images in `/app/src/main/res/drawable/` and update paths).

- Home / Input screen
![screenshot-home](docs/screenshots/home.png)

- Greeting shown
![screenshot-greet](docs/screenshots/greeting.png)

---

## Getting started

Prerequisites
- Android Studio (latest stable recommended)
- Android SDK (API 24+)
- JDK 11 or newer
- Gradle (wrapper included)

Clone the repository
```bash
git clone https://github.com/SOHAR-18/GreetingApp.git
cd GreetingApp
