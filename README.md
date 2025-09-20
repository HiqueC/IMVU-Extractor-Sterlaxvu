# IMVU Extractor

IMVU Extractor is a modern, open-source desktop application designed to be the ultimate tool for managing and extracting IMVU products. Built with React, Electron, and Python, it provides a seamless experience for downloading avatars, products, and textures from IMVU.

## ✨ Features

- **🎮 Product Management**: Add and organize your favorite IMVU products in a personal library
- **📱 Modern Interface**: Beautiful, intuitive UI built with React and Tailwind CSS
- **🌍 Multi-language Support**: Available in English and Portuguese
- **⚡ Fast Downloads**: Optimized download system with progress tracking
- **🎨 Avatar Extraction**: Extract complete avatars with all accessories and textures
- **📁 Smart Organization**: Automatic folder creation and file organization
- **🔄 Batch Processing**: Download multiple products simultaneously
- **🎯 Direct API Integration**: Real-time data synchronization with IMVU servers
- **🖥️ Cross-platform**: Works on Windows, macOS, and Linux
- **🔒 Secure**: No data collection, everything runs locally

## 🚀 Quick Start

### Prerequisites

- **Node.js** (v16 or higher)
- **Python** (v3.8 or higher)
- **Git**

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/imvu-extractor.git
   cd imvu-extractor
   ```

2. **Install dependencies**
   ```bash
   # Install Node.js dependencies
   npm install
   
   # Install Python dependencies
   pip install -r requirements.txt
   ```

3. **Setup configuration**
   ```bash
   # Copy configuration template
   cp config.py.template config.py
   cp auth_config.json.template auth_config.json
   ```

4. **Configure your IMVU credentials**
   - Edit `config.py` with your settings
   - Add your IMVU session data to `auth_config.json`

5. **Run the application**
   ```bash
   # Development mode
   npm run dev
   
   # Or run components separately
   npm start          # React frontend
   python imvu_api.py # Python backend
   npm run electron   # Electron wrapper
   ```

## 🛠️ Build from Source

### Development Setup

```bash
# Clone and setup
git clone https://github.com/yourusername/imvu-extractor.git
cd imvu-extractor
npm install
pip install -r requirements.txt

# Run in development mode
npm run dev
```

### Building for Production

```bash
# Build React app
npm run build

# Create Electron executable
npm run electron-pack

# Create installer
npm run dist
```

### Available Scripts

- `npm start` - Run React development server
- `npm run build` - Build React app for production
- `npm run electron` - Run Electron app
- `npm run dev` - Run full development environment
- `npm run dist` - Create production build and installer
- `python imvu_api.py` - Run Python API server

## 📖 Usage

1. **Launch the application**
2. **Configure your IMVU credentials** in the settings
3. **Search for products** using the product ID or URL
4. **Select download options** (textures, meshes, etc.)
5. **Choose destination folder**
6. **Start downloading** and track progress in real-time

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **Make your changes**
4. **Test thoroughly**
5. **Commit your changes** (`git commit -m 'Add amazing feature'`)
6. **Push to the branch** (`git push origin feature/amazing-feature`)
7. **Open a Pull Request**

### Development Guidelines

- Follow the existing code style
- Add tests for new features
- Update documentation as needed
- Ensure all tests pass before submitting

## 📋 System Requirements

### Minimum Requirements
- **OS**: Windows 10, macOS 10.14, or Linux (Ubuntu 18.04+)
- **RAM**: 4GB
- **Storage**: 500MB free space
- **Internet**: Stable connection required

### Recommended
- **OS**: Windows 11, macOS 12+, or Linux (Ubuntu 20.04+)
- **RAM**: 8GB or more
- **Storage**: 2GB free space
- **Internet**: High-speed broadband

## 🐛 Troubleshooting

### Common Issues

**Application won't start**
- Ensure Node.js and Python are properly installed
- Check that all dependencies are installed (`npm install` and `pip install -r requirements.txt`)

**Download failures**
- Verify your IMVU credentials are correct
- Check your internet connection
- Ensure the product ID is valid

**Permission errors**
- Run as administrator (Windows) or with sudo (Linux/macOS)
- Check folder permissions for the download directory

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with [React](https://reactjs.org/) and [Electron](https://electronjs.org/)
- UI components from [Tailwind CSS](https://tailwindcss.com/)
- Icons from [Lucide React](https://lucide.dev/)
- Python backend powered by [Flask](https://flask.palletsprojects.com/)

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/yourusername/imvu-extractor/issues)
- **Discussions**: [GitHub Discussions](https://github.com/yourusername/imvu-extractor/discussions)
- **Documentation**: [Wiki](https://github.com/yourusername/imvu-extractor/wiki)

---

<div align="center">
  <strong>Made with ❤️ for the IMVU community</strong>
</div>
