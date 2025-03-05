# Time of Day Image Classification

## Dataset
The dataset used in this project can be found at [Kaggle](https://www.kaggle.com/datasets/aymenkhouja/timeofdaydataset). It consists of images categorized into four classes representing different times of the day: morning, afternoon, evening, and night.

## Goal
The primary objective of this project is to classify images based on their time of day using deep learning algorithms. The project demonstrates the application of various deep learning techniques for image classification tasks.

## Project Description
This project utilizes deep learning models to classify images based on the time of day. The dataset is preprocessed before training multiple deep learning models. The trained models are evaluated based on their accuracy, and the best-performing model is identified. Additionally, the project includes visualizations of the dataset and learning curves of the best model.

## Project Workflow
The project follows these steps:

1. Load and preprocess the image dataset.
2. Split the dataset into training and testing sets.
3. Encode the target labels.
4. Develop multiple deep learning models using different architectures.
5. Train and evaluate the models using cross-validation.
6. Compare model accuracies to determine the best-performing one.
7. Plot learning curves for the best model.
8. Display a subset of predicted images by the best model.
9. Compute and visualize the confusion matrix.

## Deep Learning Models Used
The following deep learning models are implemented in this project:

- **Convolutional Neural Network (CNN)**: Used for extracting spatial features from images.
- **Long Short-Term Memory (LSTM)**: Experimented with to explore sequence-based learning for images.
- **Gated Recurrent Unit (GRU)**: Another recurrent-based model tested for classification performance.

## Required Libraries
Ensure the following dependencies are installed before running the project:

```bash
pip install numpy pillow scikit-learn tensorflow matplotlib
```

- **numpy**: For numerical computations.
- **Pillow**: For image processing.
- **scikit-learn**: For preprocessing and evaluation metrics.
- **tensorflow**: For deep learning model development.
- **matplotlib**: For visualization of results.

## How to Run
1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/aymenkhouja/timeofdaydataset) (or extract the dataset that is already in the image folder) and place it in the project directory.
2. Run the preprocessing script to prepare the dataset.
3. Train the deep learning models by executing the training script.
4. Evaluate the models and visualize the results.

## Results & Insights
- Model comparison results are provided to identify the best-performing model.
- Learning curves are plotted to analyze model performance.
- A confusion matrix is displayed to assess classification accuracy.
- Sample predicted images are shown to validate model predictions.

## Contributions
Contributions are welcome! Feel free to submit a pull request or open an issue for discussion.

## License
This project is open-source and available under the MIT License.

