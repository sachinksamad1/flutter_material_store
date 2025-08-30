# Material Store - A Flutter E-commerce App 🛍️
A modern, responsive e-commerce application built with Flutter, strictly following Material Design 3 guidelines. This app demonstrates a clean architecture, robust state management with Provider, and a seamless user experience for browsing and purchasing products.

## ✨ Key Features
🎨 Material Design 3 Implementation

Full M3 Theming: Complete Material 3 theming with dynamic color schemes.

Light & Dark Mode: Supports both light and dark themes with a switcher in the profile.

Material You: Utilizes the Material You design language throughout the app.

M3 Components: Proper use of modern Material components like Card, FilterChip, NavigationBar, SearchBar, etc.

## 📱 Core Functionality
Product Listing: Toggle between Grid and List views for product browsing.

Pull-to-Refresh: Easily refresh the product list with a simple gesture.

Loading & Error States: Displays Material indicators during data fetching and handles API errors gracefully.

Search & Filtering:

Real-time search functionality for products.

Category-based filtering using FilterChip.

Logic to combine both search queries and category filters.

Shopping Cart:

Add or remove products with a single tap.

Adjust the quantity of items in the cart.

Automatic calculation of the total price.

Elegant checkout process via a modal bottom sheet.

Option to clear all items from the cart.

## 🏗️ Architecture & State Management

Clean Architecture: Separated concerns with distinct layers for models, providers (business logic), and UI.

State Management: Efficiently manages app-wide state using the Provider pattern.

API Integration: Uses the http package to fetch data from the FakeStoreAPI.

Responsive Design:

Adaptive layout for tablets using NavigationRail.

Dynamically adjusts the UI for different screen sizes.

## 🚀 Getting Started
To run this project locally, follow these steps.

1. Create a new Flutter project
Bash

flutter create material_store
cd material_store
2. Update Dependencies
Replace the dependencies: section in your pubspec.yaml file with the following:

YAML

dependencies:
  flutter:
    sdk: flutter
  
  provider: ^6.1.2
  http: ^1.2.1
  cupertino_icons: ^1.0.2
3. Replace the Code
Replace the entire content of lib/main.dart with the code for this application.

4. Run the App
Finally, get the dependencies and run the application.

Bash

flutter pub get
flutter run
The app follows Material Design 3 guidelines strictly, implements all requested features, and provides a smooth, modern shopping experience. The architecture is clean and scalable, making it easy to extend with additional features.