# MoneyFlow

A modern Android application built with Kotlin and Jetpack Compose that demonstrates fundamental Android development concepts.

## 📱 Overview

This Android application serves as a basic template showcasing the latest Android development technologies including Jetpack Compose, Material3 design system, and modern Kotlin practices.

## ✨ Features

- **Modern UI**: Built with Jetpack Compose and Material3 design system
- **Kotlin-First**: Entirely written in Kotlin with modern syntax
- **Edge-to-Edge Display**: Supports modern Android edge-to-edge display
- **Dark/Light Theme**: Material3 theming with automatic theme switching
- **Composable Architecture**: Modular, reusable UI components

## 🛠 Technology Stack

### Core Technologies
- **Language**: Kotlin
- **UI Framework**: Jetpack Compose
- **Architecture**: Modern Android Architecture Components
- **Build System**: Gradle with Kotlin DSL

### Dependencies
- `androidx.core.ktx` - Kotlin extensions for Android framework
- `androidx.lifecycle.runtime.ktx` - Lifecycle-aware components
- `androidx.activity.compose` - Activity integration for Compose
- `androidx.compose.ui` - Compose UI framework
- `androidx.compose.material3` - Material3 design system components

## 📋 Requirements

- **Android Studio**: Flamingo (2022.2.1) or newer
- **Minimum SDK**: API 24 (Android 7.0)
- **Target SDK**: API 36 (Android 16)
- **Java Version**: 11

## 🚀 Getting Started

### Clone the Repository
```bash
git clone https://github.com/rwhrsbh/MoneyFlow.git
cd MoneyFlow
```

### Open in Android Studio
1. Open Android Studio
2. Select **"Open"** from the welcome screen
3. Navigate to the project directory and select the `build.gradle.kts` file
4. Click **"Open"**

### Build and Run
1. Connect an Android device or start an emulator
2. Click the **"Run"** button (green play icon) in Android Studio
3. Select your target device
4. The application will install and launch automatically

### Alternative: Command Line
```bash
# Build the project
./gradlew build

# Install and run on connected device
./gradlew installDebug
```

## 📁 Project Structure

```
app/
├── src/main/java/com/example/myapplication/
│   ├── MainActivity.kt          # Main activity entry point
│   └── ui/theme/                 # Material3 theming
│       ├── Color.kt             # App color palette
│       ├── Theme.kt             # Theme definitions
│       └── Type.kt              # Typography settings
├── src/main/res/
│   ├── drawable/                 # App icons and graphics
│   ├── mipmap-/                  # Launcher icons
│   ├── values/                   # String resources and themes
│   └── xml/                      # Backup and data extraction rules
└── src/androidTest/              # Instrumentation tests
    └── src/test/                 # Unit tests
```

## 🧪 Testing

### Unit Tests
```bash
./gradlew test
```

### Instrumentation Tests
```bash
./gradlew connectedAndroidTest
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License.

## 📞 Contact

If you have any questions or suggestions, feel free to open an issue on GitHub.

---

*Built with ❤️ using Android Studio and Jetpack Compose*
