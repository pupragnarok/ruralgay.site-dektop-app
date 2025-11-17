GitHub Copilot Chat Assistant — formatted README:

# Rural/Queer Community Desktop Applications

![App Logo](https://github.com/sniffies-nook/Sniffies-Windows-Application/blob/main/favicon.ico)

Desktop applications that wrap ruralgay.site, hitchupnow.gay, and rideorgrind.gay so they can be used as standalone apps on Windows.

## Features
- Single-window desktop wrapper for the supported sites
- Built with Electron for a native-like experience
- Packaged for easy distribution on Windows

## Getting Started

Follow these instructions to get the app running on your local machine.

### Prerequisites
- Node.js (LTS recommended)
- npm (comes with Node.js)

### Installation
1. Clone this repository:
```bash
git clone https://github.com/pupragnarok/ruralgay.site-dektop-app.git
```

2. Change to the project directory:
```bash
cd ruralgay.site-dektop-app
```

3. Install dependencies:
```bash
npm install
```

4. Start the app:
```bash
npm start
```

The app will open and load your selected website (ruralgay.site, hitchupnow.gay, or rideorgrind.gay) in a desktop window.

### Build and package
To build and package the app for distribution:
```bash
npm run electron:build
```
Built executables will be generated in the `dist` directory (depending on your electron-builder configuration).

## Configuration
- The app opens the selected website when launched. If the default site is configurable in a file (for example a configuration file under `src/`), edit that file before building. Check the repository files for any `config` or `settings` file if you need to change the default site or behavior.

## Security and Legal
- These desktop wrappers load third-party websites. Make sure you understand and comply with each website’s terms of service and privacy policy.
- Use caution when packaging and distributing apps that embed third-party content.

## Contributing
Contributions, issues, and feature requests are welcome. Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License — see the LICENSE file for details.

## Acknowledgments
- Electron
- electron-builder

## Contact
If you have questions, suggestions, or legal concerns, please open an issue on this repository or contact the maintainer (pupragnarok) via their GitHub profile.