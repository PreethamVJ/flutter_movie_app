# Movie App (Flutter)

This is a Flutter app that displays a collection of movies using the TVMaze API. The app includes multiple screens, such as a splash screen, home screen, search screen, and a details screen for each movie.

## Screens

- **Splash Screen**: Displays a picture (related to the app’s theme) when the app starts.
- **Home Screen**: Shows a list of movies with images (thumbnails), titles, and summaries fetched from the TVMaze API.
- **Search Screen**: Contains a search bar allowing users to search for movies by name. The results are fetched from the API based on the search term.
- **Details Screen**: Displays detailed information about a selected movie, including its image, summary, title, and other details.

## Features
- Displays movie thumbnails, titles, and summaries on the Home Screen.
- Allows users to search for movies via the Search Screen.
- Shows detailed information of a selected movie on the Details Screen.
- Bottom navigation bar to navigate between Home Screen and Search Screen.
- UI inspired by the Netflix design for a smooth and engaging experience.

## Installation

To run this app locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/movie-app-flutter.git
    ```

2. **Navigate to the project folder**:
    ```bash
    cd movie-app-flutter
    ```

3. **Install dependencies** using Flutter's package manager:
    ```bash
    flutter pub get
    ```

4. **Run the app**:
    ```bash
    flutter run
    ```

## API Used
The app fetches movie data from the [TVMaze API](https://www.tvmaze.com/api).

1. **Home Screen**: Fetches a list of movies using the endpoint:
   ```plaintext
   https://api.tvmaze.com/search/shows?q=all

2. **Search Screen**: Allows searching movies by name using the endpoint:
    ```plaintext
    https://api.tvmaze.com/search/shows?q=${search_term}
