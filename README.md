# Weather-Predictor
Weather Image Classification using a CNN model that analyzes images and predicts conditions like cloudy, foggy, rainy, sunrise, lightning, and more. The system processes uploaded images, outputs top predictions with confidence scores, and provides a simple interactive interface for real-time weather identification.
Weather-Predictor/
│----IN project code
├── app.py                  # UI code (runs in Google Colab)
├── model.py                # Model training code
├── data_processing.py      # Dataset splitting & preprocessing
│
├── models/
│   ├── weather.keras       # Trained CNN model
│   └── class_indices.json  # Class-label mapping
│
└── README.md               # Project documentation
