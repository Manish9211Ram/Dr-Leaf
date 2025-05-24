🌿# Dr-Leaf: Plant Disease Detection System
Dr-Leaf is an AI-powered web application designed to detect plant diseases from leaf images. By leveraging deep learning techniques, it aims to assist farmers and agricultural professionals in early disease identification, promoting timely intervention and healthier crops.

🧠 Project Overview
Objective: Provide an accessible tool for diagnosing plant diseases using image analysis.

Approach: Utilize a Convolutional Neural Network (CNN) trained on a diverse dataset of plant leaf images to classify and predict diseases.

Outcome: A user-friendly web interface where users can upload leaf images and receive instant disease predictions.

🗂️ Repository Structure
css
Copy code
Dr-Leaf/
├── app/
│   ├── trained_model/
│   │   └── README.md
│   └── [Web application files]
├── model_training_notebook/
│   └── [Jupyter notebooks for model training]
├── test_images/
│   └── [Sample images for testing]
├── README.md
app/: Contains the web application code.

trained_model/: Placeholder for the trained model file. Due to GitHub's file size limitations, the actual model is hosted in the Releases section.

model_training_notebook/: Jupyter notebooks detailing the model training process.

test_images/: Sample images to test the application's functionality.

🚀 Getting Started
Prerequisites
Python 3.x

Required Python packages (listed in requirements.txt)

Installation
Clone the repository:

bash
Copy code
git clone https://github.com/Manish9211Ram/Dr-Leaf.git
cd Dr-Leaf
Create a virtual environment (optional but recommended):

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Download the trained model:

Navigate to the Releases section.

Download the plant_disease_prediction_model.h5 file.

Place the downloaded file into the app/trained_model/ directory.

Run the application:

bash
Copy code
cd app
python app.py
The application will be accessible at http://localhost:5000.

🧪 Usage
Open the web application in your browser.

Upload a clear image of a plant leaf.

Click on the "Predict" button.

The application will display the predicted disease along with confidence scores.

📊 Model Training
The model was trained using the PlantVillage Dataset.

Training details, including data preprocessing, model architecture, and evaluation metrics, are documented in the Jupyter notebooks located in the model_training_notebook/ directory.

📁 Model File Notice
Due to GitHub's file size restrictions, the trained model file (plant_disease_prediction_model.h5) is not included directly in the repository. Instead, it is available in the Releases section. Please download it from there and place it in the app/trained_model/ directory as described in the installation steps.

🤝 Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please fork the repository and submit a pull request.

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

📬 Contact
For questions or feedback, please open an issue in the repository or contact Manish9211Ram.
