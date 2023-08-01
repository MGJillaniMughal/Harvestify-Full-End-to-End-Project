# Harvestify - Human-Disease Predictor Web App

## Overview

Harvestify is a web application that allows users to predict human-disease and get crop and fertilizer recommendations based on input parameters. This app is designed to help farmers and gardeners make informed decisions about their crops and manage plant diseases effectively.

The application is divided into three main features:

1. **Disease Detection**: Users can upload an image of a plant leaf, and the app will predict the type of disease affecting the plant.

2. **Crop Recommendation**: Users can provide specific soil and weather parameters, and the app will recommend the best crops to cultivate in that region.

3. **Fertilizer Suggestion**: Users can enter crop-specific nutrient levels, and the app will suggest the optimal fertilizer composition.

## Deployed App

The web app is deployed on Heroku and can be accessed at [https://your-heroku-app-url.com/](https://your-heroku-app-url.com/).

## Technologies Used

- Python
- Flask (for the web application)
- PyTorch (for disease prediction model)
- Scikit-learn (for crop recommendation model)
- HTML5, CSS3, Bootstrap, JavaScript, and jQuery (for the frontend)

## Usage

To use the web application, follow these steps:

1. Open the Harvestify web app in your browser.
2. Choose the appropriate section for your needs: Disease Detection, Crop Recommendation, or Fertilizer Suggestion.
3. Follow the on-screen instructions and provide the required information or upload the image (for Disease Detection).
4. Click the "Submit" button to get the results.

## Local Development

If you want to run the app locally, follow these steps:

1. Clone the repository from [GitHub](https://github.com/MGJillaniMughal/Harvestify-Full-End-to-End-Project).
2. Install the required Python libraries using `pip install -r requirements.txt`.
3. Run the app locally using `python app.py`.

Note: The app might require an API key for weather data. Make sure to create a `config.py` file and provide the API key as `weather_api_key`.

## Model Details

- Disease Detection Model: The app uses a ResNet9 model trained on a dataset of plant leaf images to predict diseases affecting the plants. The model is loaded from the file `models/plant_disease_model.pth`.

- Crop Recommendation Model: The app uses a pre-trained Random Forest model to recommend crops based on soil and weather parameters. The model is loaded from the file `models/RandomForest.pkl`.

## Contributors

- [Jillani SoftTech](https://github.com/MGJillaniMughal) - Project Developer and Maintainer

## Issues and Contributions

If you find any issues with the app or have suggestions for improvements, please open an issue on GitHub. Contributions to the project are also welcome.

## License

This project is licensed under the [MIT License](https://github.com/MGJillaniMughal/Harvestify-Full-End-to-End-Project/blob/master/LICENSE).

## Acknowledgments

- [OpenWeatherMap API](https://openweathermap.org/) for weather data.
