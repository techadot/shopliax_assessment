# Shopliax Flutter Assessment

## Project Overview

This project is a Flutter-based To-Do application that demonstrates proficiency in Flutter development, including design principles, state management, offline data storage, and API integration.

## Features

1. **To-Do Create Screen**: Add new to-do items.
2. **To-Do List Screen**: Display and manage a list of to-do items.
3. **API Data Screen**: Load and display content from an external API, with offline storage capabilities.

## Technical Requirements

- **Flutter**: The project is built using the Flutter framework.
- **State Management**: Utilizes [SetState and Provider].
- **Offline Storage**: Implements shared_preferences for local data persistence.
- **API Integration**: Fetches data from https://jsonplaceholder.typicode.com/photos.

## Project Structure

I am using a MVVM architecture, with the following structure:

```
├── Shopliax Assessment
│   ├── Lib
│   │   ├── main.dart
│   ├── src
│   │   ├── models
│   │   ├── config
│   │   ├── data
│   │   ├── providers
│   │   ├── screens
│   │   └── utils

```

## Setup and Running the Project

1. Clone the repository:
   ```
   git clone https://github.com/techadot/shopliax_assessment.git
   ```

2. Navigate to the project directory:
   ```
   cd Shopliax_assessment
   ```

3. Install dependencies:
   ```
   flutter pub get
   ```

4. Run the app:
   ```
   flutter run
   ```

## Screens

### 1. To-Do Create Screen
- Text field for entering new to-do items
- Save button to add items to the list
- Navigation back to To-Do List Screen upon successful creation

### 2. To-Do List Screen
- Displays list of saved to-do items
- Each item shows title and completion status (checkbox)
- Delete functionality for individual items

### 3. API Data Screen
- Fetches and displays photos from the provided API
- Stores first 20 items for offline access
- Displays photo thumbnails and titles
- Implements loading and error state handling

## State Management

I Leveraged a Local State Management via SetState and a more global state managemnet approach with provider to keep the application Organized.

## Offline Storage

- Uses shared_preferences to store to-do items and API data
- Ensures data persistence across app launches

## API Integration

- Fetches data from https://jsonplaceholder.typicode.com/photos
- Implements error handling and loading states
- Stores first 20 items locally for offline access

## Design Principles

- Follows Material Design guidelines
- Responsive UI that adapts to various screen sizes
- Utilizes appropriate Flutter widgets for UI components

## Additional Features

In relation to this, i wanted to integrate AI capability ( Had to cancel this Midway ), No Internet Connection banner(i wrote the code for this but didn't implement it into the app), Splash_Screen and lastly onboarding( in which i later did )  into the app

## Testing



## Build and Deploy

To build the APK:
```
flutter build apk
```

The APK will be available at `build/app/outputs/apk/app-release.apk`.

## Code Quality and Best Practices

- Follows Flutter and Dart best practices
- Implements clean architecture principles
- Code is well-documented with comments


## Contact

Samuel Odukoya - samuelodukoya14@gmail.com


Project Link: [\[The Github Repository for this project\]](https://github.com/techadot/shopliax_assessment.git)