# SwiftUI-Challenge

## Project Setup:

SwiftUI project

## Data Model:

Define a Movie struct with the following attributes:

    id: UUID
    title: String
    year: String
    genre: String
    description: String

## Use new observation framework
Use the @Observable property wrapper for managing the state of your movie data within your views.

## Movie List Screen:
Create a screen that lists movies, fetched from a statically defined array of Movie instances, showing at least the title and year of each movie.

## Coordinator pattern
Implement navigation from the list to the detail screen, but instead of directly using NavigationLink, employ a coordinator pattern to manage navigation. This encourages a separation of concerns and adheres to clean architecture principles.

## Movie Detail Screen:

Design a detail screen to display the selected movie's title, year, genre, and a detailed description.
Ensure the layout is user-friendly, utilizing SwiftUI views efficiently.

## Clean Architecture:

Organize your code following clean architecture principles. Ensure separation of concerns by dividing your project into distinct layers (e.g., presentation, domain, data).
Use view models where appropriate, and ensure they are marked with @Observable for state management.
