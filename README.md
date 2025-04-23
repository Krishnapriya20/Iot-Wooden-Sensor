# Prognostic Safety Notifications for Wooden Furnishings

This project uses IoT sensor data (humidity, temperature, pressure, etc.) to predict the safety of wooden furnishings using machine learning. The system helps to identify whether a wooden piece is at risk of structural failure based on sensor data.

## Folder Structure

```
/prognostic_safety_for_wood_furnishings/
│
├── /data/
│   └── sensor_data.csv          # Simulated IoT sensor data
├── /models/
│   └── safety_model.py          # Script for predicting safety status
├── /scripts/
│   └── preprocess_data.py       # Data preprocessing script
│   └── train_model.py           # Model training script
├── requirements.txt             # Required Python packages
└── README.md                    # Project documentation
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/prognostic-safety-for-wood-furnishings.git
   cd prognostic-safety-for-wood-furnishings
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Preprocess the data:
   ```bash
   python scripts/preprocess_data.py
   ```

2. Train the model:
   ```bash
   python scripts/train_model.py
   ```

3. Predict safety status of new furniture:
   ```bash
   python models/safety_model.py
   ```

## License

This project is licensed under the MIT License.
