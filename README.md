# X Desktop App for Linux

A standalone desktop application for X (formerly Twitter) built specifically for Linux systems. Experience X like a native desktop app without the limitations of web browsers.

## 🚀 Features

### **Native Desktop Experience**
- **Standalone Application** - Runs independently from your web browser
- **Native Performance** - Built with Electron for optimal speed and responsiveness  
- **System Integration** - Appears in your applications menu and taskbar
- **Desktop Shortcuts** - Launch directly from your desktop
- **Window Management** - Minimize, maximize, and resize like any native app

### **Official X Branding**
- **Authentic X Logo** - Uses the official X icon and branding
- **Modern Interface** - Clean, distraction-free X experience
- **Real-time Updates** - Full access to all X features and functionality
- **Login Support** - Secure authentication with your X account

### **Linux-Optimized**
- **Universal Compatibility** - Works on all major Linux distributions
- **Multiple Package Formats** - Available as AppImage, .deb, .rpm, and tar.gz
- **Lightweight** - Minimal system resource usage
- **No Dependencies** - Self-contained with all required libraries

### **Portable & Convenient**
- **USB Ready** - Portable version available for running from external drives
- **No Installation Required** - AppImage runs without installation
- **Cross-Distribution** - Same app works on Ubuntu, Fedora, Arch, and more
- **Instant Launch** - Quick startup without browser overhead

## 📦 Available Packages

| Package Type | File | Best For |
|--------------|------|----------|
| **AppImage** | `X.AppImage` | Universal - runs on any Linux system |
| **Debian Package** | `x-app_1.0.0_amd64.deb` | Ubuntu, Debian, Mint, Pop!_OS |
| **RPM Package** | `x-app-1.0.0-1.x86_64.rpm` | Fedora, RHEL, openSUSE, CentOS |
| **Generic Archive** | `x-app-1.0.0-linux-x64.tar.gz` | Manual installation on any system |
| **Source Code** | `x-app-source-1.0.0.zip` | Developers and customization |

## 🔧 System Requirements

- **Operating System:** Linux (64-bit)
- **Memory:** 512MB RAM minimum, 1GB recommended
- **Storage:** 100MB available disk space
- **Graphics:** Basic OpenGL support (standard on modern Linux)
- **Network:** Internet connection required for X functionality

## 📥 Installation

### Quick Start (AppImage)
```bash
# Download and run - no installation needed
chmod +x X.AppImage
./X.AppImage
```

### Ubuntu/Debian/Mint
```bash
sudo dpkg -i x-app_1.0.0_amd64.deb
sudo apt-get install -f  # Fix any dependencies
```

### Fedora/RHEL/CentOS
```bash
sudo rpm -i x-app-1.0.0-1.x86_64.rpm
# OR
sudo dnf install x-app-1.0.0-1.x86_64.rpm
```

### Manual Installation
```bash
tar xzf x-app-1.0.0-linux-x64.tar.gz
cd X-Portable
./launch-x.sh
```

## 🎯 Why Choose X Desktop App?

### **Better Than Web Browser**
- ✅ **Faster Performance** - No browser overhead
- ✅ **Native Notifications** - Desktop notifications for mentions and messages
- ✅ **Dedicated Window** - Separate from browser tabs and bookmarks
- ✅ **Keyboard Shortcuts** - Desktop app shortcuts and hotkeys
- ✅ **Memory Efficiency** - Uses less RAM than browser tabs

### **Linux-First Design**
- ✅ **All Distributions** - Works on Ubuntu, Fedora, Arch, openSUSE, and more
- ✅ **Package Manager Integration** - Proper installation with .deb/.rpm
- ✅ **System Theming** - Respects your desktop environment
- ✅ **No Wine Required** - Native Linux application

### **Privacy & Security**
- ✅ **No Tracking** - Clean, focused X experience
- ✅ **Local Storage** - Your data stays on your machine
- ✅ **Sandboxed** - Isolated from your browser cookies and data
- ✅ **Official X** - Direct connection to X servers, no third-party proxies

## 🛠️ Technical Details

- **Framework:** Electron + Nativefier
- **Architecture:** x86_64 (64-bit Intel/AMD)
- **Package Size:** ~70-93MB depending on format
- **Dependencies:** Self-contained (AppImage) or minimal system dependencies
- **License:** MIT
- **Maintenance:** Community-driven project

## 🐧 Supported Linux Distributions

| Distribution | Package Type | Status |
|--------------|--------------|--------|
| Ubuntu | .deb | ✅ Fully Supported |
| Debian | .deb | ✅ Fully Supported |
| Linux Mint | .deb | ✅ Fully Supported |
| Pop!_OS | .deb | ✅ Fully Supported |
| Fedora | .rpm | ✅ Fully Supported |
| RHEL/CentOS | .rpm | ✅ Fully Supported |
| openSUSE | .rpm | ✅ Fully Supported |
| Arch Linux | AppImage/tar.gz | ✅ Fully Supported |
| Manjaro | AppImage/tar.gz | ✅ Fully Supported |
| **Any Linux** | AppImage | ✅ Universal Support |

## 🚀 Quick Start Guide

1. **Download** the package for your Linux distribution from the [releases page](../../releases/latest)
2. **Install** using your package manager or run the AppImage directly
3. **Launch** X from your applications menu or desktop shortcut
4. **Login** with your X account credentials
5. **Enjoy** X as a native desktop application!

## 📸 Screenshots

> *Coming soon - Screenshots of X Desktop App in action*

## 🤝 Contributing

We welcome contributions! Help make X Desktop App better:

- 🐛 **Bug Reports** - Found an issue? Let us know!
- 💡 **Feature Requests** - Suggest new functionality
- 🔧 **Code Contributions** - Submit pull requests
- 📚 **Documentation** - Help improve our guides
- 🌍 **Translations** - Add support for more languages

## 📋 Roadmap

### v1.1.0 - Performance & UI Improvements
- [ ] Reduced memory usage and faster startup
- [ ] Dark mode detection and system theme sync
- [ ] Keyboard shortcuts and hotkeys
- [ ] Window state persistence
- [ ] Native desktop notifications

### v1.2.0 - Enhanced Features
- [ ] Multiple account support
- [ ] Custom themes and appearance options
- [ ] Screenshot and media tools
- [ ] Offline mode improvements

[View full roadmap](../../projects)

## 🆘 Support

- 📖 **Documentation** - Check our [Wiki](../../wiki)
- 🐛 **Bug Reports** - [Create an issue](../../issues/new?template=bug_report.md)
- 💡 **Feature Requests** - [Start a discussion](../../discussions/new?category=ideas)
- 💬 **General Help** - [Community discussions](../../discussions)

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚡ Quick Links

- [📥 Download Latest Release](../../releases/latest)
- [🐛 Report Issues](../../issues)
- [💡 Feature Requests](../../discussions)
- [📖 Installation Guide](../../wiki/Installation)
- [🔄 Changelog](CHANGELOG.md)

## 🌟 Show Your Support

If you find this project helpful:

- ⭐ **Star this repository**
- 🐛 **Report bugs and issues**
- 💡 **Suggest new features**
- 🔄 **Share with the Linux community**

---

**Made with ❤️ for the Linux community**

*Bringing X to Linux desktops everywhere*

![GitHub stars](https://img.shields.io/github/stars/yourusername/x-desktop-linux?style=social)
![GitHub forks](https://img.shields.io/github/forks/yourusername/x-desktop-linux?style=social)
![GitHub issues](https://img.shields.io/github/issues/yourusername/x-desktop-linux)
![GitHub license](https://img.shields.io/github/license/yourusername/x-desktop-linux)
