# Starwars App Interview Challenge

## Objective:

Create a small React Native app that demonstrates the ability to work with HTTP requests, display data in a list, and set up basic navigation and state managment.

## Fetch Data:

### Create ListScreen Component

The candidate needs to create a new screen component named ListScreen.
In this screen, make an HTTP GET request to the following endpoint: https://swapi.dev/api/starships.
Parse the received data and display a list of starships.

### Fetch Data

Use `fetch` or a library like `axios` to make the HTTP request.
Handle loading states and potential errors gracefully.

### Display Data

Display the starship's names in a list.
Ensure the list is scrollable and looks neat.

## Navigation

Ensure React Navigation and its dependencies are installed.

### Create WelcomeScreen Component

Create a WelcomeScreen Component. This will be the main component of the app. This component will have a button and navigate you to the ListScreen.

## State Management

### Setup State Management 

Ensure we have a state management library installed and its dependencies. Do the necesery setup.

### Objective

Enhance the existing app by adding state management using Redux (or any other state management library) to allow users to select starships (on the ListScreen), store the selection, and display the total number of selected starships on the WelcomeScreen.
