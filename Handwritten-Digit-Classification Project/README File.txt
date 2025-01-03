# README: Handwritten Digit Classification Using MNIST Dataset

## How to Run the Code

### Step 1: Prerequisites
Ensure you have the following installed on your system:
- Python 3.x (e.g., 3.7, 3.8, or newer)
- Jupyter Notebook or Jupyter Lab
- Required Python libraries:
  - TensorFlow
  - NumPy
  - Matplotlib
  - scikit-learn

Step 2: Setting Up the Environment
Download the following MNIST dataset files and place them in the same directory as the notebook:

train-images.idx3-ubyte
train-labels.idx1-ubyte
t10k-images.idx3-ubyte
t10k-labels.idx1-ubyte
Place the provided ML_Project_2.ipynb file in the same directory as the dataset files.

Step 3: Running the Notebook
- Open the Jupyter Notebook
- Navigate to the directory containing the notebook and click on ML_Project_2.ipynb to open it.
- Run the notebook cell by cell:
- Use the "Run" button in the Jupyter toolbar or press Shift + Enter to execute each cell sequentially.

Step 4: Outputs
- The notebook will:
	-> Load the MNIST dataset and preprocess the data.
	-> Train and evaluate both:
		Feedforward Neural Network (FFNN)
		Convolutional Neural Network (CNN)

	-> Display the following visualizations:
		Training and validation accuracy/loss graphs.
		Confusion matrices for both FFNN and CNN.
		Misclassified examples for analysis.

All results will be displayed directly in the notebook interface.

