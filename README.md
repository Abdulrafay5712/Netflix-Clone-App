# Flutter Netflix Clone

A modern, responsive Netflix clone built with Flutter. This project demonstrates a high-quality UI/UX design that works seamlessly on both Mobile and Desktop/Web platforms.

## 🚀 Features

- **Responsive Design**: Custom layouts for mobile and desktop screens.
- **Cinematic Hero Section**: Full-width banners on desktop for an immersive experience.
- **Dynamic Content**: Populated movie categories including:
  - My List
  - Popular on Netflix
  - Trending Now
  - Netflix Originals
  - Anime
- **Video Playback**: Integrated video player for trailers and previews.
- **Cross-Platform Navigation**: Bottom navigation for mobile and centered header for desktop.
- **Search & Discovery**: Dedicated search screen with real-time feedback.
- **Null Safety**: Fully migrated to Dart 3.x and null safety.

## 🛠️ Built With

- **Flutter**: UI Software Development Kit.
- **Dart**: Programming language.
- **Video Player**: For media playback.
- **Flutter Vector Icons**: Comprehensive icon library.

## 🏁 Getting Started

### Prerequisites

- Flutter SDK (v3.12.0 or higher recommended)
- Chrome or an Android/iOS emulator

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Rafay/flutter_netflix_clone_app.git
   ```
2. Navigate to the project folder:
   ```bash
   cd flutter_netflix_clone_app
   ```
3. Install dependencies:
   ```bash
   flutter pub get
   ```

### Running the App

To run on Chrome (Web):
```bash
flutter run -d chrome --no-tree-shake-icons
```

To run on a connected device/emulator:
```bash
flutter run
```

## ☁️ Deployment (Vercel)

If you are deploying this project to Vercel, use the following build settings to avoid icon-related errors:

- **Build Command**: `flutter/bin/flutter build web --release --no-tree-shake-icons`
- **Output Directory**: `build/web`

## 📄 License

This project is licensed under the MIT License.

---
Created by [Kalpesh Khandla](https://github.com/KalpeshKhandla) | Maintained and Updated by [Rafay](https://github.com/Rafay)
