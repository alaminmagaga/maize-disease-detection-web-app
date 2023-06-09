# Maize Disease Detection Web App

This web application is built using Flask and aims to detect maize diseases. It provides information on the causes of the diseases and suggests methods of control. The app analyze input images of maize plants and identify and predict potential diseases.

## Features

- **Disease Detection**: Users can upload images of maize plants to the web app, which will then analyze the images and provide a diagnosis of the disease affecting the plant.
- **Causes Information**: For each identified disease, the web app displays relevant information about the causes of the disease. Users can learn about the factors that contribute to the occurrence and spread of the disease.
- **Control Methods**: The web app also suggests effective methods for controlling and managing the detected diseases. Users can gain insights into various control strategies, such as cultural practices, chemical treatments, or biological interventions.

## Installation

To run the web app locally, follow these steps:

1. Clone this repository to your local machine using the following command:
```
git clone https://github.com/your-username/maize-disease-detection.git
```

2. Change to the project directory:
```
cd maize-disease-detection
```


3. Create a virtual environment to install the required dependencies:
```
python3 -m venv venv
```

4. Activate the virtual environment:
- For Windows:
  ```
  venv\Scripts\activate
  ```
- For macOS/Linux:
  ```
  source venv/bin/activate
  ```

5. Install the dependencies:
```
pip install -r requirements.txt
```

6. Run the Flask development server:
<br>Open your web browser and navigate to `http://localhost:5000` to access the web app.

## Usage

1. After accessing the web app, you will be presented with an interface to upload an image of a maize plant.

2. Click the "Choose File" button and select an image from your local machine that you want to analyze.

3. Once the image is uploaded, the web app will process it using machine learning algorithms to detect any potential diseases.

4. The app will display the diagnosis, providing the name of the disease affecting the plant.

5. Below the diagnosis, you can find detailed information about the causes of the disease and suggested methods of control.

6. If desired, you can repeat the process with different images to detect and learn about various maize diseases.

## Contributing

Contributions are welcome! If you encounter any issues with the web app or would like to contribute improvements, please follow these steps:

1. Fork the repository on GitHub.

2. Create a new branch from the main branch.



