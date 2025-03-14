# Plotverse: Mathematical Function Graph Plotter

An interactive web app that allows users to plot mathematical functions in real-time. Built using **Java Spring Boot** for the backend and **HTML5 + JavaScript** for the frontend. This app enables users to input mathematical functions and visualize them graphically on a canvas.

## Features

- **Interactive Graphing**: Input mathematical functions and instantly view them plotted on a graph.
- **Real-Time Plotting**: Backend (Spring Boot) processes the function, and the frontend (HTML5 + JavaScript) dynamically plots the function on an interactive canvas.
- **Simple UI**: Clean and user-friendly interface for easy interaction.

## Technologies Used

- **Backend**: Java Spring Boot
  - Spring Web
- **Frontend**: HTML5, CSS3, JavaScript
  - Canvas for drawing the graph
- **Math Parsing**: JavaScript's `eval()` function for function evaluation

## Installation

### 1. Clone the repository

git clone https://github.com/your-username/Function-Graph-Plotter.git

2. Set up the Spring Boot backend
Install Java (JDK 11 or later) on your system.

Navigate to the project directory and build the project using Maven or Gradle:

With Maven:

mvn clean install
With Gradle:

gradle build
3. Run the Spring Boot application
In the project directory, run the following command:

mvn spring-boot:run
The app will be available at http://localhost:8080.

Usage
Open http://localhost:8080 in your web browser.
Enter a mathematical function into the input field (e.g., x^2 - 2*x + 1).
Click the "Plot" button to see the graph.
The graph will be dynamically drawn on the canvas based on your input.
Example Functions
x^2 - 2*x + 1
sin(x)
cos(x)
x^3 - 3*x^2 + 2
Contributing
We welcome contributions to the Function-Graph-Plotter project! If you'd like to help out, please fork the repository, make your changes, and submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE.md file for details.

Acknowledgments
Spring Boot: For the backend framework.
HTML5 Canvas: For rendering the graph on the frontend.
JavaScript: For evaluating and plotting mathematical functions.
