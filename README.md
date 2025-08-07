# Z-Score Prediction Model

## Overview
This project provides a machine learning solution for predicting Z-Scores based on academic data. It leverages historical syllabi and student performance data to forecast Z-Scores, aiding educational institutions and students in understanding academic trends and outcomes.

## Features
- Data preprocessing and feature engineering
- Machine learning model training and evaluation
- Prediction of Z-Scores for new data
- Jupyter Notebook for interactive analysis
- Model serialization for deployment

## Project Structure
```
├── 2020_al_data_kaggle_upload_new_old_syllabi.csv   # Dataset
├── main.py                                         # Main script for training/prediction
├── model.pickle                                    # Saved ML model
├── requiremnts.txt                                 # Python dependencies
├── Z-Score.ipynb                                   # Jupyter Notebook for analysis
```

## Getting Started
### Prerequisites
- Python 3.7+
- pip

### Installation
1. Clone the repository:
   ```powershell
   git clone https://github.com/Devnath03/Machine_Learning_Z-Score-Prediction_Model.git
   cd Machine_Learning_Z-Score-Prediction_Model
   ```
2. Install dependencies:
   ```powershell
   pip install -r requiremnts.txt
   ```

### Usage
- **Run the main script:**
  ```powershell
  python main.py
  ```
- **Interactive analysis:**
  Open `Z-Score.ipynb` in Jupyter Notebook and run the cells for step-by-step analysis and prediction.

## Model Details
- The model is trained using historical academic data.
- Features are engineered from the provided CSV file.
- The trained model is saved as `model.pickle` for reuse.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes
4. Push to your branch
5. Open a pull request


## Contact
- Author: Devnath03
- GitHub: [Devnath03](https://github.com/Devnath03)

## Acknowledgements
- Kaggle for dataset resources
- Scikit-learn, Pandas, NumPy for machine learning and data processing

---
For any issues or feature requests, please open an issue on GitHub.
