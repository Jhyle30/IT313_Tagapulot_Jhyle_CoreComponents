# IT313 - React Native Core Components

**Student:** Jhyle D. Tagapulot  
**Section:** BSIT-3C
**Course:** IT313 - Mobile Programming  
**Laboratory:** Lab 6 - Introduction to React Native Core Components

## Project Description

The Student Directory Viewer is a simple React Native application that allows users to view and search student information. It displays each student's photo, name, and year level. Users can also flag students for academic advising.

## Components Used

- **View** - Organizes the layout of the application.
- **Text** - Displays student names, year levels, and labels.
- **Image** - Displays student profile pictures.
- **ScrollView** - Allows users to scroll through the student list.
- **TextInput** - Allows users to search students by name.
- **Pressable** - Handles the advising flag interaction and changes its appearance.
- **TouchableOpacity** - Demonstrates another way to handle touch interactions.

## Main Components

- **StudentCard** - Displays one student's information and advising flag.
- **StudentDirectory** - Holds the student data, search query, and flag states.
- **ProfileCard** - Demonstrates the use of View, Text, and Image.
- **ModuleSearch** - Demonstrates searching with TextInput and ScrollView.

## Features

- Displays five student profiles.
- Searches student names.
- Filters results without case sensitivity.
- Flags and unflags students for advising.
- Shows a message when no students match the search.

## Technologies

- React Native
- Expo
- TypeScript
- React Hooks

## How to Run

1. Install the dependencies using `npm install`.
2. Start the project using `npx expo start`.
3. Open the application through Expo Go or an emulator.