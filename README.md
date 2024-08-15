
# Mobility App

**Mobility App** is a web application that allows users to add points of interest (such as home, work, etc.) on a map, as well as vehicles with data like fuel consumption. Additionally, the application enables the creation of routes between two points, similar to Google Maps, and calculates the cost of these routes specifically for Spain. This unique functionality relies on local data, such as electricity and fuel prices in Spain.

## Project Status

This is a university project in a functional version, although improvements and new features are still being worked on. Development is ongoing, so frequent updates are expected.

## Installation

### Prerequisites

- Angular: v17.3.2
- Node.js: v18.18.2
- NestJS

### Installation Steps

1. **Install Node.js and Angular:**
   Ensure you have the required versions of Node.js and Angular installed.

2. **Install NestJS:**
   Run the following command to install the NestJS CLI:
   ```bash
   npm i -g @nestjs/cli
3. **Install Dependencies:**
    Once inside the project directory, run:
    ```bash
    npm install
    ```
    This will install all the necessary dependencies.
### Usage
1. **Register/Log In:**
- Access the application and sign up or log in.
2. **Features:**
- Create Vehicles: Add vehicles with fuel consumption data.
- Add Points of Interest: Mark locations on the map like home, work, etc.
- Create Routes: Set up routes between two points and calculate the route cost based on the selected vehicle.
### Contribution
Currently, external contributions are not accepted. All improvements and updates are managed by the internal development team.

### Authors
Joan Peñarrocha Centelles and Lucas Gómez García.
### Additional Documentation
- Application URL: You can access the application [here](https://app-movilidad-frontend.onrender.com). Note that it is hosted on Render using the free plan, so after a period of inactivity, it may take about 2 minutes to become active.
### Technologies and APIs Used
- Leaflet: Used for map visualization on the frontend.
- OpenRoutes: API used for creating routes and points of interest.
- Electricity Prices API (Spain): [Electricity Prices](https://api.preciodelaluz.org/v1/prices/avg?zone=PCB).
- Fuel Prices API (Spain): [Fuel Prices](https://sedeaplicaciones.minetur.gob.es/ServiciosRESTCarburantes/PreciosCarburantes/help).
### Additional Notes
Improvements and fixes are being worked on, including translating the website into English.