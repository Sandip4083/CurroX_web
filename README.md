# CurroX - Currency Converter App 💱

CurroX is a beautiful and feature-rich **currency converter** app built with Flutter.  
Convert between 160+ currencies with **live exchange rates** from a reliable API, featuring a modern UI with smooth animations.

## 🚀 Live Demo
👉 [Try CurroX Web](https://sandip4083.github.io/CurroX_web/)

## ✨ Features

- 🌍 **160+ Currencies** - Support for all major world currencies
- 📡 **Live Exchange Rates** - Real-time rates from open.er-api.com
- 🎨 **Modern UI Design** - Beautiful gradient backgrounds with smooth animations
- 🔄 **Quick Currency Swap** - One-click button to swap currencies
- 📱 **Fully Responsive** - Optimized for mobile, tablet, and web
- ⚡ **Fast & Lightweight** - Instant conversions with minimal footprint
- 🎭 **Smooth Animations** - Scale and fade transitions for better UX
- 🌐 **Country Flags** - Visual currency identification with flag emojis
- 💾 **Smart Caching** - Currencies loaded from local JSON for offline support
- 🔄 **Auto-Update** - Real-time rate updates on currency selection

## 🛠️ Technologies Used

- **Flutter** - Cross-platform framework
- **Dart** - Programming language
- **HTTP Package** - API integration
- **Auto Size Text** - Responsive text sizing
- **Exchange Rate API** - Live currency rates


## 🚀 Getting Started

### Prerequisites

Make sure you have Flutter installed on your machine.  
Check installation guide: [Flutter Installation](https://docs.flutter.dev/get-started/install)

### Installation

1. **Clone the repository:**
```bash
   git clone https://github.com/sandip4083/CurroX_web.git
```

2. **Navigate to the project folder:**
```bash
   cd CurroX_web
```

3. **Get dependencies:**
```bash
   flutter pub get
```

4. **Run the app:**
```bash
   flutter run
```

### Build for Web
```bash
flutter build web --release
```

### Build for Android
```bash
flutter build apk --release
```

### Build for iOS
```bash
flutter build ios --release
```

## 📂 Project Structure
```
lib/
├── main.dart                              # App entry point
├── pages/
│   └── currency_converter_material_page.dart  # Main converter page
└── assets/
    └── currencies.json                    # Currency data with flags
```

## 🎨 Key UI Components

- **Gradient Background** - Dark theme with blue-gray gradients
- **Glass Morphism Card** - Frosted glass effect on main card
- **Animated Result Box** - Scale animation on conversion
- **Premium Dropdowns** - Custom styled currency selectors
- **Enhanced Input Field** - Material design with icon and animations
- **Live Rate Indicator** - Color-coded status (loading/success/error)
- **Action Buttons** - Convert and Reset with gradient styling

## 🔧 Configuration

### API Integration

The app uses **Open Exchange Rates API**:
```dart
final url = "https://open.er-api.com/v6/latest/$fromCurrency";
```

No API key required - completely free!

### Adding Custom Currencies

Edit `assets/currencies.json`:
```json
{
  "USD": {
    "country": "United States",
    "name": "US Dollar",
    "flag": "🇺🇸"
  }
}
```

## 📦 Dependencies
```yaml
dependencies:
  flutter:
    sdk: flutter
  http: ^1.1.0
  auto_size_text: ^3.0.0
```

## 🌐 Supported Platforms

- ✅ Web (Chrome, Firefox, Safari, Edge)
- ✅ Android (5.0+)
- ✅ iOS (11.0+)
- ✅ Windows
- ✅ macOS
- ✅ Linux

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Sandip Kumar Sah**

- Website: [sandip4083.github.io](https://sandip4083.github.io/CurroX_web/)

## 🙏 Acknowledgments

- Exchange rates provided by [Open Exchange Rates API](https://open.er-api.com/)
- Flag emojis from Unicode standard
- UI inspiration from modern web design trends

## 📞 Support

If you like this project, please give it a ⭐️ on GitHub!

For issues and feature requests, please use the [GitHub Issues](https://github.com/sandip4083/CurroX_web/issues) page.

---

**© 2025 Sandip Kumar Sah. All rights reserved.**

Made with 💚 using Flutter
