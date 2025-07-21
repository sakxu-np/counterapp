# counterapp

A new Flutter project demonstrating state management with BLoC pattern.

## How to Run This Project

### Prerequisites

- Flutter SDK installed ([Installation Guide](https://docs.flutter.dev/get-started/install))
- Android Studio or VS Code with Flutter extensions
- An Android emulator, iOS simulator, or connected device

### Running the App

1. Clone this repository
2. Navigate to the project directory:
   ```bash
   cd counterapp
   ```
3. Get dependencies:
   ```bash
   flutter pub get
   ```
4. Run the app:
   ```bash
   flutter run
   ```

### Available Platforms

- Android: `flutter run -d android`
- iOS: `flutter run -d ios`
- Web: `flutter run -d chrome`
- macOS: `flutter run -d macos`
- Windows: `flutter run -d windows`
- Linux: `flutter run -d linux`

## Building Release Apps

### Android APK

```bash
flutter build apk --release
```

### iOS

```bash
flutter build ios --release
```

```bash
flutter build web --release
```

The web app will be built in the `build/web/` directory.

### Desktop Apps

- **macOS**: `flutter build macos --release`
- **Windows**: `flutter build windows --release`
- **Linux**: `flutter build linux --release`
