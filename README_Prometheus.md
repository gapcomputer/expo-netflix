# Netflix Mobile UI Clone: Cross-Platform React Native Streaming App

## Project Overview

This project is a comprehensive Netflix UI clone developed using React Native and Expo, offering a pixel-perfect mobile application experience across multiple platforms. The application replicates the core visual and interactive elements of the Netflix mobile app, providing users with a familiar streaming service interface.

### Core Purpose
The application aims to demonstrate a high-fidelity mobile user interface for a streaming service, showcasing advanced mobile app development techniques with React Native and Expo. It serves as both a functional demonstration and a learning resource for mobile UI design and cross-platform development.

### Key Features
- Cross-platform compatibility (iOS, Android, and Progressive Web App)
- Responsive, mobile-first design mimicking Netflix's interface
- Comprehensive navigation system using React Navigation
- Multiple screens including Home, Search, Downloads, and More sections
- Support for multiple user profiles
- Animated UI components and interactions
- Web and mobile platform support

### Technical Highlights
- Built with Expo SDK 50
- Utilizes modern React Native components and APIs
- Implements responsive design principles
- Includes mock data and screens to simulate a complete streaming app experience

The project provides a realistic, feature-rich clone of the Netflix mobile application, demonstrating advanced mobile UI development techniques and cross-platform capabilities.

## Getting Started, Installation, and Setup

### Prerequisites

- Node.js (version 16 or higher recommended)
- Yarn or npm package manager
- Expo CLI
- Smartphone or emulator (iOS/Android) or web browser

### Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/expo-netflix.git
   cd expo-netflix
   ```

2. Install dependencies:
   ```bash
   yarn install
   # or
   npm install
   ```

### Running the Application

#### Development Mode

You can run the app on multiple platforms:

- For iOS (requires Mac):
  ```bash
  yarn ios
  ```

- For Android:
  ```bash
  yarn android
  ```

- For Web:
  ```bash
  yarn web
  ```

- To start Expo development server:
  ```bash
  yarn start
  ```

#### Deployment

- Web Build:
  ```bash
  yarn web-build
  ```

### Expo Go App

For the best experience during development:
1. Install [Expo Go](https://expo.dev/go) on your mobile device
2. Scan the QR code displayed in the terminal after running `yarn start`

### Device and Platform Support

- Supports iOS, Android, and Web platforms
- Compatible with Expo SDK 50
- Requires React Native 0.73.2

### Notes

- This is a Netflix UI clone built with Expo
- Recommended to use Yarn for package management
- Ensure you have the latest version of Node.js and Expo CLI installed

## Supported Platforms

This application is a cross-platform mobile and web application compatible with:

- Android
- iOS
- Web

#### Platform Considerations
- The app is built using Expo, enabling seamless cross-platform development
- Supports both smartphone and tablet form factors (iOS tablets specifically supported)
- Designed primarily for mobile platforms with a portrait orientation
- Web version available with consistent UI across platforms

#### Platform-Specific Notes
- Android: Minimum version requirements not explicitly specified
- iOS: Supports iPad via `supportsTablet` configuration
- Web: Fully functional web application with responsive design

## Running the App

### Prerequisites

Ensure you have the following installed:
- Node.js
- Expo CLI
- Expo Go mobile app (for mobile testing)
- Xcode (for iOS development, macOS only)
- Android Studio (for Android development)

### Running on Simulator/Emulator

#### iOS
```bash
npx expo start --ios
```

#### Android
```bash
npx expo start --android
```

### Running on Web
```bash
npx expo start --web
```

### Running on Physical Device

1. Install the Expo Go app on your mobile device
2. Start the development server:
```bash
npx expo start
```
3. Scan the QR code with the Expo Go app (iOS) or the Expo Go app's QR code scanner (Android)

### Additional Notes
- Ensure you have installed all project dependencies by running `npm install` or `yarn install` before starting the app
- For best performance, use the latest version of Expo and React Native

## Key Screens and Features

This Netflix UI clone offers a comprehensive streaming app experience with multiple key screens and features:

### Home Screen
- Displays a curated selection of content
- Features scrollable content categories 
- Includes preview thumbnails and featured content

### Content Browsing
- Dedicated screens for Movies and TV Shows
- Ability to browse different genres and content types
- Smooth, intuitive navigation between content sections

### Search Functionality
- Comprehensive search screen
- Browse and find content quickly
- Supports content discovery and filtering

### User Profile Management
- Add and manage multiple user profiles
- Personalized user icons
- Easy profile switching

### My List
- Save and manage favorite content
- Quick access to personally curated watchlist
- Customize and edit saved content

### Downloads
- Download content for offline viewing
- Manage downloaded media
- Track downloaded shows and movies

### Additional Features
- Cast connection support
- Notifications management
- App settings and customization
- Video playback modal
- Web view integration for additional content

The app mimics the core Netflix mobile experience, providing a seamless and engaging content browsing and streaming interface.

## Build and Deployment

### Prerequisites

- Ensure you have Expo CLI installed globally: `npm install -g expo-cli`
- Node.js and Yarn or npm package manager

### Build for Different Platforms

#### Web Build
To create a production web build, run:
```bash
yarn web-build
```
The built files will be generated in the `web-build` directory.

#### iOS and Android Builds
This project uses Expo, which provides simplified build processes:

1. For iOS:
```bash
expo build:ios
```

2. For Android:
```bash
expo build:android
```

### Distribution

The app is set up for distribution through:
- Expo Client
- App Store (iOS)
- Google Play Store (Android)

### Build Configuration

- Current Version: 0.0.2
- Supported Platforms: iOS, Android, Web
- App Scheme: `netflixclone`
- Orientation: Portrait mode

## Additional Notes

### Performance Considerations

The application is designed as a cross-platform mobile UI clone with web support, utilizing Expo SDK 50. When deploying or developing, consider the following:

- The Progressive Web App (PWA) version is not yet production-ready
- Performance may vary across different devices and platforms
- Recommended to test thoroughly on target devices

### Compatibility and Limitations

- Supports iOS, Android, and Web platforms
- Web version optimized for mobile device viewing
- Some platform-specific features may have limited functionality

### Development Environment

- Requires Node.js and Yarn package manager
- Uses Expo CLI for development and deployment
- Recommended Node.js version: Check `.nvmrc` file for specific version

### Code Quality

- Implements ESLint with Airbnb configuration
- Uses Prettier for code formatting
- Follows React Native and Expo best practices

### Potential Expansion Areas

- Implement full authentication flow
- Add more comprehensive error handling
- Enhance mock data with more realistic content
- Improve cross-platform UI consistency

### Known Issues

- Web support is experimental
- Some platform-specific behaviors may differ
- Mock data used for demonstration purposes

### Security Note

- This is a UI clone and should not be used for production authentication
- Does not include real Netflix streaming functionality
- Uses mock data and simulated interactions

### Accessibility

- Basic accessibility features implemented
- Recommended to conduct thorough accessibility testing
- Some platform-specific accessibility features may vary

## Contributing

We welcome contributions to the Netflix UI Clone project! By contributing, you help improve the project for everyone.

### How to Contribute

1. Fork the repository
2. Create a new branch for your feature or bugfix
3. Make your changes
4. Commit with a clear and descriptive commit message
5. Push to your fork
6. Submit a pull request

### Code Style Guidelines

- This project uses ESLint with Airbnb configuration and Prettier for code formatting
- Run `yarn lint` to check for linting issues before submitting a pull request
- Ensure your code follows the existing code style and conventions

### Development Setup

- Use `yarn` for package management
- Run `yarn dev` to start the development server
- Use Expo CLI for development and testing

### Testing

- While specific test coverage is not currently implemented, ensure that your changes do not break existing functionality
- Test your changes thoroughly on both iOS and Android platforms

### Reporting Issues

- Use GitHub Issues to report bugs or suggest enhancements
- Provide a clear description of the issue, including steps to reproduce
- Include your environment details (OS, Expo SDK version, etc.)

### Code of Conduct

- Be respectful and inclusive
- Collaborate constructively
- Help maintain a welcoming community for all contributors

### Additional Notes

- This project supports iOS, Android, and Web (PWA) platforms
- Ensure compatibility across these platforms when making changes

## License

This project is licensed under the MIT License. 

### License Details
- **Type**: MIT License
- **Copyright**: © 2019 Caleb Nance

The MIT License is a permissive free software license that allows you to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software, subject to the conditions specified in the license.

### Key Permissions
- Commercial use
- Modification
- Distribution
- Private use

### Conditions
- Include the original license and copyright notice in any substantial portion of the software

For the full license text, please see the [LICENSE](LICENSE) file in the repository.