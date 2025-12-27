# Kalender V Beta

A modern, elegant calendar and productivity application with robust Firebase integration and beautiful light/dark themes.

## 🎨 Features

### Theme System
- **Elegant Light Mode**: Soft white backgrounds (#f8f9fb) with subtle contrast
- **AMOLED Dark Mode**: True black (#000000) optimized for OLED displays with muted text
- **Secondary Themes**: Pastel and High-contrast options for different preferences
- **Auto Mode**: Follows system preferences and time-based switching

### Core Functionality
- 📅 **Calendar Management**: Multiple calendars with color coding
- ✏️ **Event Management**: Create, edit, delete, and drag-and-drop events
- 🔄 **Recurring Events**: Support for daily, weekly, biweekly, monthly, and yearly patterns
- 👥 **Collaboration**: Share calendars with team members
- 💬 **Chat/Messaging**: Built-in encrypted communication
- ✅ **TODO Management**: Task lists with categories
- 📊 **Shift Planning**: Workforce scheduling features
- 📤 **ICS Export**: Export events to standard calendar format
- 🔍 **Search**: Find events, todos, and memos quickly
- 📱 **PWA Support**: Install as a progressive web app

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (for Firebase services)
- HTTPS or localhost (Firebase requirement)

### Quick Start
1. Open `kalender_rai_final_v7.html` in your browser via HTTP(S) server
2. Register a new account or use demo mode
3. Start creating events and managing your calendar

### Running Locally
```bash
# Using Python
python3 -m http.server 8080

# Using Node.js
npx http-server -p 8080

# Then open: http://localhost:8080/kalender_rai_final_v7.html
```

## 🎨 Design System

### Colors
- **Light Primary**: #2563eb (Blue)
- **Light Accent**: #4da3ff (Sky Blue)
- **Light Background**: #f8f9fb (Soft White)
- **Dark Primary**: #4da3ff (Sky Blue)
- **Dark Background**: #000000 (True Black)
- **Dark Text**: #e8ecf5 (Muted White)

### Typography
- System fonts: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial

## 🔧 Technical Stack

- **Frontend**: React 18 (UMD), Tailwind CSS (CDN)
- **Backend**: Firebase (Auth, Firestore, Storage)
- **Build**: Standalone (no bundler required)
- **Babel**: Standalone for JSX transformation

## 📝 Recent Updates

See [CHANGELOG.md](CHANGELOG.md) for detailed version history.

### Latest (V Beta - December 2025)
- Complete theme system overhaul with elegant Light and AMOLED Dark modes
- 390+ lines of UI improvements across components
- Enhanced Firebase integration with fallback mechanisms
- Improved error handling and robustness
- Better accessibility with focus states
- Fixed CSS issues and added missing icons

## 🔒 Security

- Firebase authentication with secure rules
- End-to-end encryption for chat messages
- Input sanitization for exports
- Safe deletion confirmations

## 📱 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

This is an automated refresh project. For issues or suggestions, please open an issue in the repository.

## 📄 License

See repository license file.

## 👥 Credits

Developed and maintained by tejari49. Refreshed with modern design and improved reliability.

---

**Note**: This application requires Firebase configuration. The included configuration is for demonstration purposes. For production use, please set up your own Firebase project.