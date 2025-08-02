# ERP Android App

A modern, beautiful Android ERP application built with Jetpack Compose and Material 3 design.

## 🚀 Quick APK Download

**To get the APK file:**
1. This repository is set up with GitHub Actions
2. Every push will automatically build the APK
3. Download the APK from the "Actions" tab → Latest workflow run → Artifacts

## 📱 Features

- **Modern UI**: Material 3 design with Jetpack Compose
- **Authentication**: Login/Registration screens
- **Dashboard**: Analytics and quick actions
- **ERP Modules**: 
  - Products management
  - Customers management
  - Purchase Orders
  - Reports and analytics
- **API Integration**: Retrofit with your .NET backend
- **MVVM Architecture**: Clean, maintainable code

## 🛠️ Technical Stack

- **UI**: Jetpack Compose, Material 3
- **Architecture**: MVVM, Clean Architecture
- **Dependency Injection**: Hilt
- **Networking**: Retrofit, OkHttp
- **Async**: Kotlin Coroutines
- **Navigation**: Navigation Compose
- **Database**: Room (for offline support)
- **Image Loading**: Coil

## 🔧 Setup Instructions

### Prerequisites
- Android Studio (for development)
- .NET Web API backend running on `http://localhost:5000`

### Installation
1. Clone this repository
2. Open in Android Studio
3. Sync project with Gradle files
4. Run on device/emulator

### API Configuration
The app is configured to connect to:
- **Emulator**: `http://10.0.2.2:5000`
- **Physical Device**: Update to your computer's IP address

## 📦 APK Generation

### Option 1: GitHub Actions (Recommended)
1. Push code to GitHub
2. Go to Actions tab
3. Download APK from latest workflow run

### Option 2: Local Build
```bash
./gradlew assembleDebug
```
APK will be at: `app/build/outputs/apk/debug/app-debug.apk`

### Option 3: Android Studio
1. Build → Build Bundle(s) / APK(s) → Build APK(s)
2. APK will be generated automatically

## 🔗 Backend Integration

This app connects to your .NET Web API with these endpoints:
- `POST /api/Auth/login` - User authentication
- `GET /api/Products` - Get products list
- `POST /api/Products` - Create product
- `GET /api/Customers` - Get customers list
- `POST /api/Customers` - Create customer
- `GET /api/PurchaseOrders` - Get purchase orders
- `POST /api/PurchaseOrders` - Create purchase order

## 📱 Screenshots

- Login Screen with Material 3 design
- Dashboard with analytics cards
- Products list with search functionality
- Customers management
- Purchase Orders tracking
- Reports and analytics

## 🚀 Getting Started

1. **Install APK**: Download from GitHub Actions or build locally
2. **Configure Backend**: Ensure your .NET API is running
3. **Update API URL**: Change from `10.0.2.2:5000` to your server IP
4. **Login**: Use any credentials (demo mode)

## 📄 License

This project is licensed under the MIT License.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

---

**Built with ❤️ using Jetpack Compose and Material 3** 