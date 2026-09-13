# Flutter Todo App

A simple and elegant todo list application built with Flutter and Provider state management.

## Features

- ✅ Add new todos with title and description
- ✅ Mark todos as complete/incomplete
- ✅ Delete todos
- ✅ Clean and intuitive UI
- ✅ State management with Provider

## Getting Started

### Prerequisites

- [Flutter](https://flutter.dev/docs/get-started/install) installed
- [VS Code](https://code.visualstudio.com/) with Flutter extension
- A device or emulator for testing

### Installation

1. Clone this repository:
```bash
git clone https://github.com/aimenhassan223-svg/flutter-todo-app.git
cd flutter-todo-app
```

2. Get dependencies:
```bash
flutter pub get
```

3. Run the app:
```bash
flutter run
```

## Project Structure

```
lib/
├── main.dart                 # App entry point
├── models/
│   └── todo.dart            # Todo model and TodoProvider
├── screens/
│   ├── home_screen.dart     # Main todo list screen
│   └── add_todo_screen.dart # Screen to add new todos
└── widgets/
    └── todo_item.dart       # Individual todo list item widget
```

## Dependencies

- **provider**: State management solution
- **cupertino_icons**: iOS-style icons

## Usage

1. **Add a Todo**: Tap the floating action button (+) and fill in the title and description
2. **Complete a Todo**: Check the checkbox next to a todo to mark it as complete
3. **Delete a Todo**: Tap the trash icon to remove a todo

## Development

### VS Code Setup

1. Install the Flutter extension in VS Code
2. Open the project folder
3. Run `flutter pub get` to install dependencies
4. Press F5 or run `flutter run` to start the app

### Building

```bash
# Build for Android
flutter build apk

# Build for iOS
flutter build ios
```

## Contributing

Feel free to fork this repository and submit pull requests for any improvements!

## License

MIT License
