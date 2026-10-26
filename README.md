# Flutter API Posts App

A Flutter application that fetches posts from a REST API and displays them in a clean, scrollable interface.

## Features
## App Screenshot

![Flutter API Posts App Screenshot](screenshots/posts-screen.png)

- Fetches posts from JSONPlaceholder REST API.
- Displays post titles and body text.
- Shows a loading indicator while fetching data.
- Handles API errors with a retry button.
- Uses `FutureBuilder` for asynchronous UI updates.
- Displays posts using `ListView.builder`.

## Tech Stack

- Flutter
- Dart
- HTTP package
- REST API
- JSON

## API Used

JSONPlaceholder: https://jsonplaceholder.typicode.com/posts

## Getting Started

1. Install Flutter and Git.
2. Clone this repository.
3. Open the project folder in your terminal.
4. Install dependencies:

   ```bash
   flutter pub get
   ```

5. Run the application:

   ```bash
   flutter run -d chrome
   ```

## Project Structure

- `lib/main.dart` — application entry point and posts screen.
- `pubspec.yaml` — project dependencies and configuration.

## Learning Objectives

This project demonstrates my practical learning of Flutter UI development, HTTP requests, JSON parsing, asynchronous programming, `FutureBuilder`, and API error handling.

## Author

**Nayab Afzal**

GitHub: https://github.com/NayabAfzal258

---

This project was created as part of my journey toward becoming a Flutter Developer.
