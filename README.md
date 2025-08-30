# Material Store - A Flutter E-commerce App 🛍️
A modern, responsive e-commerce application built with Flutter, strictly following Material Design 3 guidelines. This app demonstrates a clean architecture, robust state management with Provider, and a seamless user experience for browsing and purchasing products.

## 📸 Screenshots

![Screenshot1](/screenshots/Screenshot_1_flutter_material_store.jpg)  ![Screenshot2](/screenshots/Screenshot_2_flutter_material_store.jpg)  ![Screenshot3](/screenshots/Screenshot_3_flutter_material_store.jpg)

## ✨ Key Features

  - 🎨 Material Design 3 Implementation

  - Full M3 Theming: Complete Material 3 theming with dynamic color schemes.

  - Light & Dark Mode: Supports both light and dark themes with a switcher in the profile.

  - Material You: Utilizes the Material You design language throughout the app.

  - M3 Components: Proper use of modern Material components like Card, FilterChip, NavigationBar, SearchBar, etc.

## 📱 Core Functionality

 -  Product Listing: Toggle between Grid and List views for product browsing.

  - Pull-to-Refresh: Easily refresh the product list with a simple gesture.

  - Loading & Error States: Displays Material indicators during data fetching and handles API errors gracefully.

  - Search & Filtering:

      - Real-time search functionality for products.

      - Category-based filtering using FilterChip.

      - Logic to combine both search queries and category filters.

  - Shopping Cart:

      - Add or remove products with a single tap.

      - Adjust the quantity of items in the cart.

      - Automatic calculation of the total price.

      - Elegant checkout process via a modal bottom sheet.

      - Option to clear all items from the cart.

## 🛠️ Tech Stack & Dependencies

Framework: [Flutter](https://flutter.dev/)

Language: [Dart](https://dart.dev/)

API: [FakeStoreAPI](https://fakestoreapi.in/) for product data.

Packages:

  1. `http`: For making network requests to the API.

  2. `provider`:  Process of managing and sharing application state across the widget tree

  3. `cupertino_icons`: Sets of icon assets 

## 🏗️ Architecture & State Management

  - Clean Architecture: Separated concerns with distinct layers for models, providers (business logic), and UI.

  - State Management: Efficiently manages app-wide state using the Provider pattern.

  - API Integration: Uses the http package to fetch data from the FakeStoreAPI.

  - Responsive Design:

      - Adaptive layout for tablets using NavigationRail.

      - Dynamically adjusts the UI for different screen sizes.

## 🚀 Getting Started
Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

Prerequisites

  - Flutter SDK installed (version 3.x.x or higher)

  - An IDE like Android Studio or VS Code with Flutter plugins.

  - A device or emulator to run the app.

Installation

  1. Clone the repository:
```
git clone https://github.com/sachinksamad1/flutter_material_store.git
cd flutter_material_store
```
  2. Install dependencies: Run the following command in your terminal to fetch all the necessary packages.
```
 flutter pub get
```
  3. Run the application: Connect your device or start an emulator, then run the app.
```
flutter run
```

## 📂 Project Structure
The project is structured to separate concerns, making it easy to understand and maintain.
```
lib/
└── main.dart             # The main entry point of the application.
```
## 🤝 Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

  - Fork the Project

  - Create your Feature Branch (git checkout -b feature/AmazingFeature)

  - Commit your Changes (git commit -m 'Add some AmazingFeature')

  - Push to the Branch (git push origin feature/AmazingFeature)

  - Open a Pull Request

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Made with ❤️ by SACHIN K SAMAD
