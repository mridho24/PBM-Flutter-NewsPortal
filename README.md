# 📱 News Hub - Flutter Mobile Application

A Flutter-based news application developed as a final project for the **Mobile-Based Programming** course. This application provides users with a streamlined interface to browse, read, and categorize news articles from various sources.

## 👨‍💻 Student Information

- **Name**: Muhammad Ridho
- **NPM**: 2208107010064

## 🔍 Application Overview

News Hub is a comprehensive mobile application that fetches real-time news data from the NewsAPI service. The app is designed with modern UI/UX principles and implements core mobile development concepts including API integration, data persistence, and responsive layouts.

## ⚙️ Key Features

- **Dynamic News Feed**: Real-time news updates with image thumbnails and brief descriptions
- **Detailed Article View**: Full article reading experience with proper formatting
- **Category Navigation**: Browse news by categories (Technology, Business, Sports, etc.)
- **User Authentication**: Secure login and registration system
- **Bookmarking**: Save articles for later reading
- **Dark/Light Theme**: Customizable app appearance based on user preference
- **Search Functionality**: Find specific news articles by keywords

## 🛠️ Technical Implementation

- **State Management**: Provider pattern for efficient app-wide state control
- **Local Storage**: Secure data persistence using shared_preferences
- **HTTP Requests**: RESTful API integration with http package
- **UI Components**: Custom widgets and animations for enhanced user experience
- **Navigation**: Intuitive app navigation using bottom navigation and page routing

## 📚 Libraries & Dependencies

```yaml
dependencies:
  flutter:
    sdk: flutter
  http: ^0.13.5
  provider: ^6.0.5
  shared_preferences: ^2.1.0
  cached_network_image: ^3.2.3
  flutter_spinkit: ^5.1.0
  url_launcher: ^6.1.10
  intl: ^0.18.0
  connectivity_plus: ^3.0.3
```

## 📁 Project Structure

```
lib/
├── models/            # Data models
├── providers/         # State management
├── screens/           # App screens
│   ├── auth/          # Login/Registration
│   ├── home/          # Main news feed
│   ├── article/       # Article details
│   ├── category/      # Category view
│   └── profile/       # User profile
├── services/          # API and data services
├── utils/             # Helper functions
├── widgets/           # Reusable UI components
└── main.dart          # Application entry point
```

## 📸 Screenshots

- Home Screen - Displays trending news articles
- Article Detail - Shows complete article content
- Categories - Categorized news browsing
- Profile Screen - User information and settings

## 🚀 Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/muhammadridho/flutter-news-hub.git
   ```

2. Navigate to project directory:

   ```bash
   cd flutter-news-hub
   ```

3. Install dependencies:

   ```bash
   flutter pub get
   ```

4. Run the application:
   ```bash
   flutter run
   ```

## 📋 Future Enhancements

- Push notifications for breaking news
- Offline reading capability
- Social media sharing integration
- Personalized news feed based on user preferences
- Voice command navigation

---
# PBM-Flutter-NewsPortal
