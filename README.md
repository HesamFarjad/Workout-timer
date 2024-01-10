


This repository contains a simple React application for a workout timer. The application includes a main component App, a calculator component Calculator, and a sound toggle component ToggleSounds.
App Component (App.js)
The App component serves as the main container for the workout timer. It displays the current time, allows users to toggle sound, and renders the Calculator component for configuring workout details.
Key Features:
* Real-time clock display using the Intl.DateTimeFormat API.
* Dynamically generates workout options based on the time of day (AM/PM).
* Utilizes a Calculator component for configuring workout parameters.
Calculator Component (Calculator.js)
The Calculator component is responsible for setting up workout parameters and calculating the total workout duration. It features sliders for selecting the type of workout, number of sets, exercise speed, and break length. The component also provides options to increment or decrement the total workout time.
Key Features:
* Dynamic calculation of workout duration based on user input.
* Audio feedback with a click sound (optional and toggleable).
* Real-time updates and display of workout duration.
* Interactive UI for configuring workout settings.
ToggleSounds Component (ToggleSounds.js)
The ToggleSounds component is a simple button that allows users to enable or disable sound feedback during the workout. It updates the state in the parent component (App) to control the sound's availability.
Key Features:
* Toggle between sound on/off with a button click.
* Reflects the current sound status through emoji icons.
Usage
To use the workout timer:
* 		Clone the repository.
* 		Install dependencies using npm install or yarn install.
* 		Run the application using npm start or yarn start.

<img width="1437" alt="Screenshot 2024-01-10 at 08 55 46" src="https://github.com/HesamFarjad/Workout-timer/assets/81914229/6ad24439-c66f-4304-9ded-216265a7de1a">
