# Flutter CRUD App

A modern Flutter application demonstrating CRUD (Create, Read, Update, Delete) operations with a clean and intuitive user interface. This app serves as a practical example of implementing basic data management operations in Flutter.

## Features

- Create new items with custom details
- View and manage items in a clean interface
- Update existing items
- Delete unwanted items
- Material Design 3 implementation
- Responsive UI with search functionality

## Screenshots

<p>
  <img src="images/one.png" width=250px hspace="10" alt="Screenshot 1">
  <img src="images/two.png" width=250px hspace="10" alt="Screenshot 2">
  <img src="images/three.png" width=250px hspace="10" alt="Screenshot 3">
  <img src="images/four.png" width=250px hspace="10" alt="Screenshot 4">
</p>

## Project Structure

```
lib/
├── main.dart              # Application entry point
├── home_screen.dart       # Main screen with item list
├── item_add_screen.dart   # Screen for adding new items
├── popup_widget.dart      # Reusable popup widget
└── todo model/
    └── todo_services.dart # Business logic and API services
```

## Dependencies

- Flutter SDK: >=3.1.0-163.1.beta <4.0.0
- http: ^1.1.0 - For API communication
- cupertino_icons: ^1.0.2

## Getting Started

1. **Prerequisites**
   - Flutter SDK installed on your machine
   - An IDE (Android Studio/VS Code)
   - Basic knowledge of Flutter/Dart

2. **Installation**
   ```bash
   # Clone the repository
   git clone [repository-url]

   # Navigate to project directory
   cd crud

   # Install dependencies
   flutter pub get

   # Run the app
   flutter run
   ```

## Development Resources

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)
- [Online documentation](https://docs.flutter.dev/)

## Contributing

Feel free to submit issues and enhancement requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
