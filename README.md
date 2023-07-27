
Birthday Reminder App

This is a simple React application that displays a list of people's birthdays and allows you to clear the list. The application uses React hooks to manage the state and display the data.

How to Use

Clone the repository to your local machine.
Navigate to the project directory.
Run npm install to install the dependencies.
Run npm start to start the development server.
Open your web browser and go to http://localhost:3000 to view the app.
Features

The app displays a list of people's birthdays along with their names, ages, and images.
It shows the total number of birthdays for the current day.
You can click the "clear all" button to clear the list of birthdays.
Components

App.js: The main component that initializes the state, passes the data to the List component, and renders the "clear all" button.
List.js: A reusable component that receives the list of people's data as props and renders the list of birthdays.
Data

The data for the birthdays is stored in a separate file called data.js as an array of objects, where each object represents a person with their id, name, age, and image.

Sample Data

The sample data provided in data.js includes the information for five people with their names, ages, and image URLs.

