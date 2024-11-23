# Rock vs Mine Prediction

## Overview
This project demonstrates a machine learning model to predict whether a given sonar signal corresponds to a **Rock** or a **Mine**. The model is implemented in Python using **Logistic Regression** and the popular **Scikit-learn** library.

## Features
- Binary classification using a **Logistic Regression Model**.
- Data preprocessing, including splitting the dataset into training and testing sets.
- Model evaluation using **accuracy score**.
- A predictive system to classify unseen sonar data.

## Dataset
The dataset used is the **Sonar Dataset**, where each row represents a sonar signal. The last column contains the labels:
- `R`: Rock
- `M`: Mine

### Dataset Attributes
- **Input Features**: 60 numerical values representing sonar signal frequencies.
- **Target Labels**: `R` (Rock) and `M` (Mine).

## Project Structure
The project contains a single Python file:
- `Rock_VS_Mine_Prediction.py`: Contains the complete implementation of the project, from data loading to model training and prediction.

## Requirements
The following Python libraries are required to run the project:
- `numpy`
- `pandas`
- `scikit-learn`

You can install these libraries using pip:
```bash
pip install numpy pandas scikit-learn
```

## How to Run the Project
1. Clone this repository or download the `Rock_VS_Mine_Prediction.py` file.
2. Ensure the `sonar.csv` dataset is in the same directory as the Python file.
3. Run the Python script:
   ```bash
   python Rock_VS_Mine_Prediction.py
   ```
4. The script will:
   - Load and preprocess the dataset.
   - Train the Logistic Regression model.
   - Display the training and test accuracies.
   - Allow you to input data for prediction and classify it as either a **Rock** or a **Mine**.

## Key Results
- **Training Accuracy**: X% (Replace with actual value)
- **Test Accuracy**: Y% (Replace with actual value)

## Predictive System
You can test the predictive system by modifying the `input_data` variable in the script with new feature values. The system will output:
- `The object is Rock`
- `The object is Mine`

## Example Input and Output
### Example Input:
```python
input_data = (0.0200, 0.0371, 0.0428, 0.0207, 0.0954, 0.0986, ...)
```
### Example Output:
```
['R']
The object is Rock
```

## Future Improvements
- Experiment with other classification algorithms such as **Random Forests** or **SVMs**.
- Perform hyperparameter tuning to improve model accuracy.
- Incorporate a graphical user interface (GUI) for easier use.

## License
This project is licensed under the MIT License. Feel free to use and modify it as needed.

## Acknowledgments
- The **Sonar Dataset** was used for training and evaluation.
- Special thanks to the open-source community for providing robust libraries like Scikit-learn.

---
If you have any questions or suggestions, feel free to reach out!
