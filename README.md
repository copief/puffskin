# PUFF Skin Changer

<div align="center">

![Version](https://img.shields.io/badge/version-0.1.0-blue.svg)
![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

**Professional League of Legends Skin Changer**

[Features](#-features) • [Installation](#-installation) • [Usage](#-usage) • [Building](#-building) • [Security](#-security)

</div>

---

## 📋 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Screenshots](#-screenshots)
- [Installation](#-installation)
- [Usage](#-usage)
- [Building from Source](#-building-from-source)
- [Project Structure](#-project-structure)
- [Security](#-security)
- [Contributing](#-contributing)
- [License](#-license)

## 🎮 About

PUFF Skin Changer is a professional, feature-rich application for League of Legends that allows players to customize their in-game champion skins. Built with Electron and modern web technologies, it provides a seamless experience for managing and applying custom skins.

## ✨ Features

### Core Features
- **🎨 Skin Management**: Browse and apply custom skins for all champions
- **⚡ Real-time Application**: Apply skins instantly without restarting the game
- **🔍 Advanced Search**: Quick search functionality with alphabet navigation
- **⭐ Favorites System**: Save and quickly access your favorite champions
- **🌐 Multi-language Support**: English and Turkish language support
- **🎯 Grid View**: Customizable grid layout for better skin browsing

### Automation Features
- **🤖 Auto Accept**: Automatically accept match found notifications
- **🚫 Auto Ban**: Automatically ban selected champions in ranked matches
- **✅ Auto Pick**: Automatically pick selected champions in ranked matches
- **🎨 Auto Skin**: Automatically apply selected champion's skin
- **📄 Auto Skin Page**: Automatically switch to champion's skin page when selected in-game

### Customization
- **🎨 Custom Skins**: Import and manage your own custom skin files (.fantome)
- **🎨 Theme Customization**: Customizable accent colors and appearance settings
- **⚙️ Performance Settings**: Optimize application performance
- **🔔 Notifications**: Get notified when skins are applied

### Technical Features
- **🔒 Secure Authentication**: Firebase-based secure user authentication
- **💾 Secure Configuration**: Encrypted configuration management
- **🔄 Auto-update Support**: Automatic updates via GitHub Releases
- **🛡️ Security**: Hardware ID verification and secure token management
- **📊 Performance Optimized**: Efficient caching and resource management

## 📸 Screenshots

> Screenshots will be added here

## 🚀 Installation

### Prerequisites
- Windows 10/11 (64-bit)
- League of Legends installed
- Administrator privileges (for first-time setup)

### Download
1. Go to the [Releases](https://github.com/Adolphaa/puffskin/releases) page
2. Download the latest `PUFF-Skin-Changer-x.x.x-x64-portable.exe`
3. Extract or run the executable

### First-time Setup
1. Run the application
2. The application will automatically detect your League of Legends installation
3. If not detected, manually select your League installation path
4. Restart the application if needed

## 💻 Usage

### Applying Skins
1. Launch PUFF Skin Changer
2. Browse champions using the sidebar or search bar
3. Select a champion to view available skins
4. Click on a skin to apply it
5. The skin will be applied automatically to your game

### Custom Skins
1. Go to the Custom Skins section
2. Click "Import Custom Skin"
3. Select your `.fantome` file
4. Add metadata (name, image, description)
5. Apply the custom skin like any other skin

### Automation Settings
1. Open Settings
2. Navigate to the Automation section
3. Enable desired features:
   - Auto Accept
   - Auto Ban/Pick
   - Auto Skin
4. Configure champion preferences

### Settings
- **Appearance**: Customize theme colors, brightness, and animations
- **Performance**: Configure cache settings and optimization
- **Notifications**: Enable/disable skin application notifications

## 🔨 Building from Source

### Prerequisites
- Node.js 18+ and npm
- Git

### Clone the Repository
```bash
git clone https://github.com/Adolphaa/puffskin.git
cd puffskin
```

### Install Dependencies
```bash
npm install
```

### Development Mode
```bash
npm run dev
```

### Build for Production
```bash
# Portable build
npm run build

# Windows installer
npm run build:installer

# All Windows targets
npm run build:win
```

### Build Output
Built files will be in the `dist/` directory.

## 📁 Project Structure

```
puffskin/
├── src/                    # Source code
│   ├── assets/            # Images and static assets
│   ├── modules/           # Core modules
│   │   ├── custom-skins-manager.js
│   │   ├── favorites-manager.js
│   │   ├── secure-config-manager.cjs
│   │   ├── skin-id-mapping-manager.cjs
│   │   ├── theme-manager.js
│   │   └── ui-utils.js
│   ├── index.html         # Main HTML
│   ├── renderer.js        # Renderer process
│   ├── styles.css         # Styles
│   └── translations.js    # i18n translations
├── tools/                 # External tools and utilities
├── customs/               # Custom skin files
├── build/                 # Build configuration
├── main.js               # Main Electron process
├── preload.cjs           # Preload script
└── package.json          # Project configuration
```

## 🔒 Security

### Security Features
- **Encrypted Configuration**: All sensitive data is encrypted
- **Hardware ID Verification**: Device-based authentication
- **Secure Token Management**: Encrypted token storage
- **Firebase Security**: Secure backend with Firebase Admin SDK
- **IPC Channel Whitelist**: Restricted IPC communication

### Important Notes
- Never share your Firebase service account keys
- Keep your authentication tokens secure
- The application stores encrypted data in `%APPDATA%/copief`

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Development Guidelines
- Follow the existing code style
- Add comments for complex logic
- Test your changes thoroughly
- Update documentation if needed

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- League of Legends community
- Electron team
- Firebase team
- All contributors and testers

## 📧 Contact

For issues, questions, or suggestions:
- Open an issue on [GitHub Issues](https://github.com/Adolphaa/puffskin/issues)
- Check the [Discussions](https://github.com/Adolphaa/puffskin/discussions) page

---

<div align="center">

**Made with ❤️ for the League of Legends community**

[⬆ Back to Top](#puff-skin-changer)

</div>

