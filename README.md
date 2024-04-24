# Machine Failure Prediction Model

## Introduction
This project aims to predict machine failures using machine learning techniques. The model, developed using Python in a Jupyter Notebook environment, utilizes a combination of Keras, TensorFlow, and scikit-learn libraries for data preprocessing, model construction, training, and evaluation.

## Dependencies
- pandas
- scikit-learn
- numpy
- TensorFlow
- Keras

## Dataset
The dataset used in this project is stored in a CSV file named "machine failure.csv". It consists of various features such as UDI, Product ID, Type, Air temperature, Process temperature, Rotational speed, Torque, Tool wear, and multiple failure categories.

## Usage
1. **Clone the Repository**: Clone this repository to your local machine.

2. **Install Dependencies**: Ensure you have all the required dependencies installed. You can install them using pip:
   ```
   pip install pandas scikit-learn numpy tensorflow keras
   ```

3. **Open Jupyter Notebook**: Open the Jupyter Notebook file `Machine_Failure_Prediction.ipynb` in your Jupyter Notebook environment.

4. **Run the Notebook**: Execute each cell in the notebook sequentially to load the dataset, preprocess the data, build the machine failure prediction model, train the model, and evaluate its performance.

5. **Evaluate Results**: After running all the cells, review the output to observe the model's accuracy on the validation and test sets.

## Model Architecture
The neural network model architecture consists of:
- Input layer with 11 neurons (input features)
- Two hidden layers with 7 and 3 neurons, respectively, using ReLU activation function
- Output layer with 1 neuron using Sigmoid activation function for binary classification

## Performance
- **Validation Set Accuracy**: 99.9%
- **Test Set Accuracy**: 99.85%

## Future Improvements
- Experiment with different neural network architectures and hyperparameters to potentially improve model performance.
- Explore additional feature engineering techniques to enhance predictive capabilities.

## License
This project is licensed under the [MIT License](LICENSE).
