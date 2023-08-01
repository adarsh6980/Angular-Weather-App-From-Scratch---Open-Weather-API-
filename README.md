# WeatherApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.1.5.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.


Angular-Weather-App-From-Scratch---Open-Weather-API-
Angular Weather App From Scratch - Open Weather API

Angular Weather App

Weather App Screenshot image
![image](https://github.com/adarsh6980/Angular-Weather-App-From-Scratch---Open-Weather-API-/assets/69494124/97481657-b83b-4f5b-8b08-6e3303e1323b)


Description The Angular Weather App is a simple web application that allows users to check the current weather conditions for a specified location. It leverages the OpenWeather API to retrieve weather data and presents it in a user-friendly manner.

Features Get the current weather details for a specific city or location. Display the weather conditions including temperature, humidity, wind speed, and Min-temp and Max-temp. Responsive design: The app is designed to work well on various devices, including desktops, tablets, and mobile phones.

Prerequisites Before running the Angular Weather App, ensure you have the following installed:

Node.js (v14 or higher) Angular CLI (v16 or higher)

Installation Clone this repository to your local machine: bash Copy code git clone https://github.com/your-username/your-weather-app.git Navigate to the project directory: bash Copy code cd your-weather-app Install the required dependencies: Copy code npm install Configuration To make API calls to OpenWeather API, you need to obtain an API key:

Sign up for a free account at https://openweathermap.org/. Once you have your API key, create a new file named config.ts in the src/app directory. Add the following content to the config.ts file: typescript Copy code export const environment = { production: false, apiKey: 'YOUR_OPENWEATHER_API_KEY', }; Replace 'YOUR_OPENWEATHER_API_KEY' with your actual API key.

Usage To start the development server and run the app, use the following command:

sql Copy code npm start The app will be available at http://localhost:4200/.

Contributing We welcome contributions to the Angular Weather App. To contribute, please follow these steps:

Fork the repository on GitHub. Create a new branch with a descriptive name: git checkout -b feature/your-feature. Make your changes and commit them: git commit -m "Add feature: your feature description". Push your changes to your fork: git push origin feature/your-feature. Submit a pull request to the main repository. License The Angular Weather App is open-source software licensed under the MIT License.

Acknowledgments The Angular team and the community for providing an excellent framework. OpenWeatherMap for their free API service. Contact If you have any questions, suggestions, or feedback, feel free to contact us at your.email@example.com.

Replace the placeholders with your actual project information, and don't forget to include any specific setup instructions or additional details that might be relevant to your project.

Remember to keep your README file up-to-date as the project evolves, and it will serve as a useful reference for other developers who want to contribute or use your Angular Weather App. Happy coding!
