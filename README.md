# Smart E‑Moped Dashboard Flutter App

This repository contains a minimal Flutter application alongside a preconfigured VS Code **DevContainer**. It’s set up to make development on macOS (including Apple Silicon like M3), Linux, or Windows consistent and easy.

## Features
- 📱 **Flutter app**: Basic "Hello world" app you can expand to your needs.
- 🐳 **DevContainer**: Uses `ghcr.io/cirruslabs/flutter:latest` Docker image with the Flutter SDK and required VS Code extensions (`Dart` & `Flutter`) preinstalled.
- ✅ Ready to run on [VS Code Remote - Containers](https://code.visualstudio.com/docs/devcontainers/overview) or [GitHub Codespaces](https://github.com/features/codespaces).

## Getting Started
1. Clone this repository.
2. Open it in VS Code with the **Dev Containers** extension installed.
3. When prompted, **Reopen in Container**. VS Code will build the container using the definition in `.devcontainer/devcontainer.json`.
4. Once inside the container, run your Flutter app with:

```bash
flutter run
```

You can target web (`flutter run -d chrome`), Android, or iOS depending on installed tooling.

## Project Structure
- `.devcontainer/` – Development container configuration.
- `lib/main.dart` – Source code of the Flutter app.
- `pubspec.yaml` – Flutter package configuration.

---

Feel free to modify and build upon this template for your Smart E‑Moped Dashboard project!
