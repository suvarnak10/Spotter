# Spotter App for Business Location Ranking

The Spotter App is a web application that helps users planning to start a business by providing them with ranked location suggestions based on sustainable factors such as proximity to competitors and competitor ratings. Users can fill out a form with details about their business, including business name, type, location, target customers, and company scale. The app then allows users to select specific locations on a map, and the backend utilizes the Selenium package in Python, along with Flask, to calculate and display ranked location suggestions.

## Features

- **Form Submission**: Users can fill out a form with business details, including name, type, location, target customers, and company scale.

- **Map Interaction**: The app provides a Leaflet map interface that allows users to select specific locations where they are considering starting their business.

- **Ranking Algorithm**: The backend calculates a ranking for each selected location based on factors such as proximity to competitors, competitor ratings, and the number of ratings.


## Setup Instructions

1. **Prerequisites**: Make sure you have Python and Flask installed on your machine.

2. **Clone the Repository**: Clone this repository to your local machine using the following command:
   
   ```
   git clone https://github.com/your-username/spotter-app.git
   ```

3. **Install Dependencies**: Navigate to the project directory and install the required dependencies:

   ```
   cd spotter-app
   pip install -r requirements.txt
   ```

4. **ChromeDriver Setup**: Download the ChromeDriver executable and specify its path in the Python code where indicated. You can download ChromeDriver from the official website: https://sites.google.com/chromium.org/driver/

5. **Run the App**: Start the Flask app by running the following command:

   ```
   python app.py
   ```

6. **Access the App**: Open your web browser and go to http://localhost:5000 to access the Spotter App.

## Usage

1. **Home Page**: The app's home page provides an introduction to the Spotter App.

2. **Form Submission**: Navigate to the form page where you can provide details about your business. Fill out the form with information such as business name, type, location, target customers, and company scale. Once the form is submitted, you will be redirected to the map page.

3. **Map Interaction**: On the map page, use the Leaflet map to select specific locations where you are considering starting your business.

4. **View Rankings**: After selecting locations on the map, the app will calculate and display rankings for each location based on proximity to competitors, competitor ratings, and the number of ratings.

## Contributing

Contributions to the Spotter App are welcome! If you have any suggestions, bug fixes, or new features to propose, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to modify this README to suit your specific project details and formatting preferences. Make sure to update placeholders like `your-username` and provide accurate information about your project.
