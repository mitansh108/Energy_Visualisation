# Renewable Energy vs Energy Independence: A Global Exploration
This project aims to visualize the relationship between renewable energy adoption and energy independence across nations. Through an interactive scrollytelling approach, users can explore historical trends, regional dynamics, and future possibilities. By leveraging advanced data visualization techniques, this platform informs policy decisions and raises awareness about the impact of renewable energy on global energy systems.

Motivation

Energy independence has become a key metric of national security and economic stability. Countries highly dependent on energy imports face vulnerabilities such as price fluctuations, geopolitical risks, and supply chain disruptions. This project is inspired by:

The urgent need to combat climate change.
The growing interest in renewable energy technologies.
The lack of accessible tools for understanding the interplay between energy policies and independence.
Project Overview

Objective: To visualize how renewable energy adoption influences energy independence across countries globally.
Interactive Narrative: Through a scrollytelling approach, users explore data-driven insights regarding energy production, consumption, and renewable adoption over time.
Datasets Used

We used datasets from reputable sources:

United Nations Trade Data: Detailed records of global energy imports and exports.
U.S. Energy Information Administration (EIA): Comprehensive statistics on energy production, consumption, and costs.
Kaggle Renewable Energy Dataset: Historical data on renewable energy capacity (1965-2022).
Tools & Technologies

Frontend:
React: Used for dynamic and responsive user interfaces, ensuring a seamless user experience.
Scrollama: Integrated with React for scrollytelling transitions, syncing scrolling actions with data updates and animations.
Visualization:
Three.js: Powering the interactive 3D globe, enabling smooth animations and real-time rendering of energy-related data.
D3.js: Used for creating data-driven visualizations, including line charts, radar graphs, and streamgraphs, with smooth transitions.
Backend:
Spring Boot: A robust backend service for handling APIs and ensuring seamless communication between the frontend and database.
MySQL: Used for storing and managing large datasets, ensuring quick retrieval and reliable storage of energy data.
Features

Interactive Scrollytelling: Allows users to explore how renewable energy adoption impacts energy independence across various regions.
Data Visualizations: Displays multiple types of visualizations such as line charts, radar graphs, and streamgraphs to represent energy-related data.
Real-Time Data: Data visualizations update in real-time using Three.js for 3D rendering and D3.js for interactive charts.
For executing the React Application
In the project directory, i.e Data-Visualiszation-front-end/ run the below command
### `npm install`

the above code installs necessary dependency for the project

### `npm start`

Then open [http://localhost:3000](http://localhost:3000) to view it in your browser.

(Note: install npm if the error shows as npm symbol not recognised)

For executing the Springboot application

In the backend project directory, i.e Data-Visualiszation-back-end/ run the below command

### `mvn spring-boot:run`

(Note: install maven and Java version 17 or above if the error shows as mvn symbol not recognised and/or java symbol not recognised)

