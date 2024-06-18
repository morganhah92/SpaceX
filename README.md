# SpaceX App: Instructions

## Initial Setup

### Configure Gradle
Add necessary dependencies for Jetpack Compose, Retrofit, Coroutines, Unit Testing, and Firebase in `build.gradle` files.

## App Architecture

### MVI Clean Architecture
Implement the app using MVI (Model-View-Intent) Clean architecture to ensure a scalable and maintainable codebase.

### Create a Model
Define data classes for the SpaceX API information via Postman.

### Create a Repository
Implement a repository class that will use Retrofit to fetch data from the SpaceX API.

### Create a ViewModel
Implement a ViewModel that will use the repository to load data and expose it to the UI.

## User Interface

### Create Composable Functions
Create UI screens with Jetpack Compose.

### Implement Navigation
Use Jetpack Navigation to navigate between different screens.

## Firebase Authentication

### Set Up Firebase Authentication
Configure Firebase for login and sign-up functionality.

### Implement Login and Sign-Up
Create composable functions for login and sign-up screens and integrate them with Firebase authentication.

## Fetch Data

### Get Data from SpaceX API
Use Retrofit and Coroutines to fetch data from the SpaceX API.

### Display Data
Use the ViewModel to expose data to the UI and display it using composable functions.

## Testing

### Write Unit Tests
Use JUnit and Mockito to write unit tests.

![dashboard](images/dashboard.jpeg)
![list](images/list.jpeg)
![details](images/details.jpeg)






