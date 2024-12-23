# ReState 🏠

Welcome to **ReState**, a simple real estate browsing app built with **React Native**, **Expo**, and **Appwrite** as the backend. Users can easily log in using their Google account and explore real estate listings.

## Features 🚀

- **Google Authentication**: Secure and seamless login with Google using Appwrite.
- **Browse Listings**: Explore various real estate listings with an intuitive UI.
- **Cross-Platform**: Works on Android, iOS, and Web, thanks to Expo.

---

## Getting Started

Follow these steps to set up the project locally:

### 1. Install Dependencies

Run the following command to install the necessary dependencies:

```bash
npm install
```

### 2. Set Up Your Appwrite Backend

1. **Install and Set Up Appwrite**:

   - Follow the [Appwrite installation guide](https://appwrite.io/docs/installation) to set up Appwrite on your server or cloud.

2. **Create a Project in Appwrite**:

   - Go to the Appwrite console and create a new project named `ReState`.

3. **Set Up OAuth Provider**:

   - Enable Google as an OAuth2 provider in your Appwrite project. [Guide here](https://appwrite.io/docs/authentication#oauth2).

4. **Create Database and Collections**:

   - Create a database to store real estate listings.

5. **Add API Keys and Environment Variables**:
   - Configure your `.env` file with the following variables:
     ```env
     EXPO_PUBLIC_APPWRITE_ENDPOINT=<your-appwrite-endpoint>
     EXPO_PUBLIC_APPWRITE_PROJECT_ID=<your-project-id>
     ```

### 3. Start the App

Start the development server:

```bash
npx expo start
```

- Open the app in:
  - A [development build](https://docs.expo.dev/develop/development-builds/introduction/).
  - An [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/).
  - An [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/).
  - The [Expo Go](https://expo.dev/go) app.

---

## File Structure

Here's a high-level overview of the project's structure:

```
.
├── app/
│   ├── auth/          # Google authentication logic
│   ├── components/    # Reusable UI components
│   ├── screens/       # App screens like Home, Listing Details, etc.
│   ├── utils/         # Utility functions
│   └── App.js         # Main entry point
├── assets/            # Images, fonts, and other static assets
├── .env               # Environment variables
├── README.md          # Project documentation
└── package.json       # Dependencies and scripts
```

---

## Future Enhancements 🛠️

- **Search and Filter Listings**: Enable users to search and filter listings by location, price, and more.
- **Favorite Listings**: Allow users to save their favorite listings.
- **Real-Time Updates**: Implement real-time updates for new listings using Appwrite's subscription feature.
- **Dark Mode**: Add support for dark mode.

---

## Resources 📚

- [React Native Documentation](https://reactnative.dev/)
- [Expo Documentation](https://docs.expo.dev/)
- [Appwrite Documentation](https://appwrite.io/docs/)
- [Learn React Native Tutorial](https://reactnative.dev/docs/tutorial)

---

## Join the Community 🌐

Connect with other developers and share your journey:

- [Expo on GitHub](https://github.com/expo/expo)
- [Appwrite on GitHub](https://github.com/appwrite/appwrite)
- [React Native Community](https://reactnative.dev/help)
- [Expo Discord](https://chat.expo.dev)

---

## Contributing 🤝

We welcome contributions! Please feel free to submit issues and pull requests for new features or bug fixes.

---

## License 📄

This project is licensed under the MIT License.
