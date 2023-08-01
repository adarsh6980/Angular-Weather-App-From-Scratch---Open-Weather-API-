# Angular-Weather-App-From-Scratch---Open-Weather-API-
Angular Weather App From Scratch - Open Weather API 


Angular Weather App

Weather App Screenshot
![image](https://github.com/adarsh6980/Angular-Weather-App-From-Scratch---Open-Weather-API-/assets/69494124/83525f35-0150-4ef0-9922-35be801e9ebd)


Description
The Angular Weather App is a simple web application that allows users to check the current weather conditions for a specified location. It leverages the OpenWeather API to retrieve weather data and presents it in a user-friendly manner.

Features
Get the current weather details for a specific city or location.
Display the weather conditions including temperature, humidity, wind speed, and Min-temp and Max-temp.
Responsive design: The app is designed to work well on various devices, including desktops, tablets, and mobile phones.


Prerequisites
Before running the Angular Weather App, ensure you have the following installed:

Node.js (v14 or higher)
Angular CLI (v16 or higher)


Installation
Clone this repository to your local machine:
bash
Copy code
git clone https://github.com/your-username/your-weather-app.git
Navigate to the project directory:
bash
Copy code
cd your-weather-app
Install the required dependencies:
Copy code
npm install
Configuration
To make API calls to OpenWeather API, you need to obtain an API key:

Sign up for a free account at https://openweathermap.org/.
Once you have your API key, create a new file named config.ts in the src/app directory.
Add the following content to the config.ts file:
typescript
Copy code
export const environment = {
  production: false,
  apiKey: 'YOUR_OPENWEATHER_API_KEY',
};
Replace 'YOUR_OPENWEATHER_API_KEY' with your actual API key.

Usage
To start the development server and run the app, use the following command:

sql
Copy code
npm start
The app will be available at http://localhost:4200/.

Contributing
We welcome contributions to the Angular Weather App. To contribute, please follow these steps:

Fork the repository on GitHub.
Create a new branch with a descriptive name: git checkout -b feature/your-feature.
Make your changes and commit them: git commit -m "Add feature: your feature description".
Push your changes to your fork: git push origin feature/your-feature.
Submit a pull request to the main repository.
License
The Angular Weather App is open-source software licensed under the MIT License.

Acknowledgments
The Angular team and the community for providing an excellent framework.
OpenWeatherMap for their free API service.
Contact
If you have any questions, suggestions, or feedback, feel free to contact us at your.email@example.com.

Replace the placeholders with your actual project information, and don't forget to include any specific setup instructions or additional details that might be relevant to your project.

Remember to keep your README file up-to-date as the project evolves, and it will serve as a useful reference for other developers who want to contribute or use your Angular Weather App. Happy coding!
