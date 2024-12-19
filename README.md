# React Native Goals App

This project is a simple React Native app that allows users to set and manage goals. Users can input goals and view them in a scrollable list.

## Features
- Add new goals using a text input and button.
- Display a list of goals in a scrollable view.
- Automatically assigns a unique ID to each goal.

## Technologies Used
- **React Native**: Framework for building mobile apps.
- **JavaScript**: Programming language used for app logic.
- **Expo**: Framework and platform for universal React applications.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/react-native-goals-app.git
   cd react-native-goals-app

2. Install Dependencies: Ensure you have Node.js and Expo CLI installed, then run:

npm install


3. Start the App:

npx expo start

This will launch the development server, allowing you to view the app on a simulator or physical device via the Expo Go app.



App Structure

Components

TextInput: For entering new goals.

Button: To add the goal to the list.

FlatList: To render the list of goals.


Hooks

useState:

enteredGoalText: Stores the text entered by the user.

courseGoals: Stores the list of goals.



Styling

Uses StyleSheet for managing styles.


Code Explanation

Key Functions

goalInputHandler: Updates the state when text is entered in the input field.

addGoalHandler: Adds the entered goal to the list and clears the input field.


Styling Overview

appContainer: Main container with padding and flex layout.

inputContainer: Styled to arrange input and button side-by-side.

goalItem: Each goal is styled with padding, background color, and rounded corners.


Example Usage

1. Enter your goal in the text input.


2. Press the Add Goal button.


3. View the goal added to the list below.



Screenshots

(Add your app screenshots here)

Contributing

Contributions are welcome! If you have suggestions for improvements, feel free to open an issue or submit a pull request.

License

This project is licensed under the MIT License.



