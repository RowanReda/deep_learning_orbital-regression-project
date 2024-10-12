# Orbital Regression Project

## Objective
The objective of this task is to build a neural network model to predict the orbital path of a spacecraft based on time steps. The model should be trained on a dataset of time steps and corresponding y-positions, and evaluated using metrics such as mean squared error, mean absolute error, and R-squared score.

## Dataset Description
The dataset used for this task is a CSV file named orbit.csv, which contains two columns: time_steps and y. The time_steps column represents the time steps at which the spacecraft's position is recorded, and the y column represents the corresponding y-positions of the spacecraft.

## Steps to Run the Code in Google Colab
1. Upload the orbit.csv file to your Google Colab environment.
2. Copy and paste the provided code into a new Colab notebook.
3. Adjust the file path in the pd.read_csv() function to match the location of your orbit.csv file.
4. Run the code cell by cell to execute the neural network model training and evaluation.

## Dependencies
- NumPy: !pip install numpy
- Pandas: !pip install pandas
- TensorFlow: !pip install tensorflow
- Matplotlib: !pip install matplotlib
- Scikit-learn: !pip install scikit-learn
- Keras: !pip install keras

