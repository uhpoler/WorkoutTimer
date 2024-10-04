# WorkoutTimer

**WorkoutTimer** is a customizable fitness timer app built with React that helps users plan and manage their workout sessions efficiently. With the ability to choose workout types, set exercise duration, and toggle sounds, this app is designed to adapt to various workout preferences while providing real-time duration updates.

## Features

- **Dynamic Workout Plans**: Users can select from different workout routines, with each type offering a varying number of exercises based on the time of day (AM/PM).
- **Timer Management**: Calculates the total workout duration based on the number of sets, speed of exercises, and break times.
- **Sound Toggle**: Option to enable or disable workout sounds for each session.
- **Real-Time Updates**: The app continuously tracks and displays the current time while updating the workout duration in real-time.
- **Customizable Settings**: Adjust the number of sets, speed, and break duration for personalized workout sessions.
- **Responsive Design**: Adapted for smooth usage across devices.

## Components

The project is organized into the following React components:

- **App**: The main component that manages the workout state, time, and sound settings.
- **Calculator**: Handles the workout logic, allowing users to customize sets, speed, and break durations while calculating the total workout time.
- **ToggleSounds**: Provides an interface to toggle sound on or off during the workout.
  
## How It Works

1. Upon loading, the app displays the current time and updates it every second.
2. Users can select their workout type, the number of sets, exercise speed, and break duration.
3. The app dynamically calculates the workout duration based on user input and displays it in minutes and seconds.
4. Users can toggle sound on or off for their workout session using the **ToggleSounds** component.
5. A button interface allows users to adjust the workout duration manually.

## Technologies Used

- **React**: For building the user interface and managing state.
- **React Hooks**: Uses `useState`, `useEffect`, and `useMemo` to handle state, side effects, and performance optimization.
- **JavaScript (ES6+)**: Core language for building the app’s functionality.
- **CSS**: Provides styling and ensures a responsive layout.
- **Audio**: The app includes sound effects that can be toggled during the workout session.

## Screenshots

![image](https://github.com/user-attachments/assets/22be5159-42f5-4296-b569-fd427a7e7747)

## Installation

To run the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/WorkoutTimer.git
   ```
2. **Install the dependencies**:
   ```bash
   npm install
   ```
3. **Start the application**:
   ```bash
   npm start
   ```

   The app will be available at `http://localhost:3000`.
