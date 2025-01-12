# Namer App

A Flutter project that generates and manages random English word pairs. The app features the ability to save favorite word pairs, view their history, and switch seamlessly between different pages using adaptive layouts.

## Features

- **Random Word Pair Generation:** Generates random English word pairs using the `english_words` package.
- **Favorites Management:** Mark word pairs as favorites and manage them on a dedicated favorites page.
- **History Tracking:** Tracks previously generated word pairs with an animated history list.
- **Responsive Design:** Adaptive layout for mobile and desktop screens using `BottomNavigationBar` and `NavigationRail`.
- **Theming:** Modern material design with a customizable color scheme.
- **State Management:** Uses `provider` package for state management.

## Getting Started

### Prerequisites

Ensure you have the following installed on your system:

- [Flutter SDK](https://docs.flutter.dev/get-started/install)
- Dart 3.0+
- An IDE (e.g., [VS Code](https://code.visualstudio.com/) or [Android Studio](https://developer.android.com/studio))

### Installation Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/namer_app.git
   cd namer_app
   ```

2. Install dependencies:

   ```bash
   flutter pub get
   ```

3. Run the application:
   ```bash
   flutter run
   ```

## Project Structure

- **`main.dart`**: The main entry point of the app.
- **State Management**: Uses `ChangeNotifier` and `Provider` for managing app state (`MyAppState`).
- **UI Pages**:
  - `GeneratorPage`: Displays random word pairs and options to like or generate new pairs.
  - `FavoritesPage`: Displays the list of saved favorite word pairs.
- **Widgets**:
  - `BigCard`: Shows the current word pair in a styled card.
  - `HistoryListView`: Animates the history of generated word pairs.

## Packages Used

- [english_words](https://pub.dev/packages/english_words): Generates random English word pairs.
- [provider](https://pub.dev/packages/provider): Simplifies state management.

## Upcoming Enhancements

- Add a search and sort feature for favorites.
- Persist data using local storage (e.g., `SharedPreferences` or `Hive`).
- Implement light/dark theme toggling.
- Add export/share functionality for favorite word pairs.

## Resources

- [Flutter Documentation](https://docs.flutter.dev/): Tutorials, samples, and API references.
- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
