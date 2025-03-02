# README - Dog Breed Classification Project

## Overview
This project implements a **dog breed classification system** using **Convolutional Neural Networks (CNNs) and ResNet architectures**. The dataset used includes:
1. **Dog Breed Images (DBI)** dataset
2. **Stanford Dogs Dataset (SDD)**

The project includes:
- A **custom CNN** trained on DBI.
- **ResNet-18, ResNet-34, and ResNeXt32** models fine-tuned on DBI.
- **A dataset classification model** distinguishing between SDD and DBI.
- Comparative analysis of model performances.
- **Discussions of Tasks 1 to 7 included in the Jupyter Notebook file.**
- **Answers to Questions 1 to 7 provided in the report.pdf file.**

## Prerequisites
Ensure you have the following installed:
- **Python 3.8+**
- **PyTorch**
- **Torchvision**
- **Pandas**
- **Matplotlib**
- **NumPy**
- **Google Colab** (recommended for running the code)
- **Kaggle API** (for dataset download)

## Running the Code
### 1. **Set Up Environment**
- If using **Google Colab**, simply upload `dog_breed_classifier_final.ipynb` and run all cells.
- If running locally, ensure that dependencies are installed:
  ```sh
  pip install torch torchvision pandas matplotlib numpy kaggle
  ```

### 2. **Download and Prepare Datasets**
- The datasets are downloaded directly using `kagglehub` inside the notebook.
- If running locally, ensure your Kaggle API key is set up.
- The code automatically processes and subsets the datasets before training.

### 3. **Train and Evaluate Models**
- The notebook runs different models including:
  - **Custom CNN on DBI**
  - **ResNet-18, ResNet-34, and ResNeXt32 fine-tuned on DBI**
  - **ResNet-18 for dataset classification (SDD vs. DBI)**
- Each model is trained for **10 epochs** by default.
- Training and validation accuracy are plotted for performance comparison.

### 4. **Comparing Performance**
- The notebook evaluates:
  - Accuracy on **DBI test set**
  - Accuracy on **entire SDD dataset**
  - **Cross-dataset generalization performance**
  
### 5. **Customizing Training**
- Hyperparameters (epochs, learning rate, batch size) can be modified in the training function.
- Different optimizers (SGD, Adam) can be tested.

## Expected Outputs
- Plots showing **training vs. validation accuracy**.
- **Comparison of CNN vs. ResNet models**.
- **Cross-dataset performance analysis**.
- **Final accuracy on DBI and SDD test sets**.

## Notes
- If any issues arise with dataset downloads, verify your **Kaggle API configuration**.
- Training times may vary depending on hardware (Colab GPU recommended).
- Ensure that the notebook is **run sequentially** to avoid dataset path errors.

For any questions, refer to the comments in the notebook! 

