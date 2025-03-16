# Octopi - A Powerful Cursor IDE Extension

![Build Status](https://github.com/markvshaney/Octopi/actions/workflows/ci.yml/badge.svg)

Octopi is a powerful extension for the Cursor IDE that enhances your development experience with advanced features and intelligent code assistance.


## Features

- 🚀 Seamless integration with Cursor IDE
- 🎯 Intelligent code suggestions
- 🔍 Advanced code navigation
- ⚡ Performance optimizations
- 🛠️ Customizable settings


## Installation

1. Download the latest .vsix package from the [Releases](https://github.com/markvshaney/Octopi/releases) page
2. Open Cursor IDE
3. Press Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (macOS)
4. Type 'Install from VSIX' and select the command
5. Choose the downloaded .vsix file

## Development

### Prerequisites

- Node.js 16.x or later
- npm 7.x or later
- Cursor IDE


### Setup

`ash
# Clone the repository
git clone https://github.com/markvshaney/Octopi.git
cd Octopi

# Install dependencies
npm install

# Build the extension
npm run compile

# Watch for changes during development
npm run watch
``n
### Testing the Extension

1. Press F5 in VS Code to start debugging
2. In the new Extension Development Host window:
   - Press Ctrl+Shift+P (Cmd+Shift+P on macOS)
   - Type 'Hello World' and select the command
   - You should see a notification message


## Building

To create a VSIX package:

`ash
npm run package
``n
The generated .vsix file can be found in the root directory.

## CI/CD

This project uses GitHub Actions for continuous integration and deployment:

- Automated builds on push and pull requests
- Multiple Node.js version testing (16.x, 18.x)
- Automatic VSIX package generation
- Release automation for tagged commits

## Contributing

1. Fork the repository
2. Create your feature branch (git checkout -b feature/amazing-feature)
3. Commit your changes (git commit -m 'Add some amazing feature')
4. Push to the branch (git push origin feature/amazing-feature)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

If you encounter any issues or have questions, please [open an issue](https://github.com/markvshaney/Octopi/issues/new)
