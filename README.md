# Hybrid Sequential CNN-GNN Model for Soybean Leaf Disease Classification

This repository contains the implementation of a **Hybrid Sequential CNN-GNN model** designed for **Soybean Leaf Disease Classification**.

## Dataset

The following dataset was used in this project:

1. **Soybean Diseased Leaf Dataset** - A high-quality image dataset containing soybean leaves affected by **10 different diseases**.
   - [Soybean Diseased Leaf Dataset](https://www.kaggle.com/datasets/sivm205/soybean-diseased-leaf-dataset)

## Approach

The project follows a structured approach to build and evaluate the **Hybrid Sequential CNN-GNN model**, leveraging:

- **MobileNetV2** for feature extraction.
- **Graph Convolutional Network (GCN)** for relational learning.
- **Explainable AI (XAI)** for model interpretation, including **Grad-CAM** and **Eigen-CAM**.

## Repository Structure

- `cnn-soybean.ipynb` - CNN-based model using MobileNetV2.
- `gnn-soybean.ipynb` - GNN-based approach for graph-based disease classification.
- `parallel-cnn-gnn.ipynb` - Parallel architecture combining CNN and GNN.
- `seq-cnn-gnn.ipynb` - Proposed **Hybrid Sequential CNN-GNN model**.
- `seq-cnn-gnn-xai.ipynb` - Explainable AI (XAI) version of the sequential CNN-GNN model, including **Grad-CAM** and **Eigen-CAM**.
- `seq-gnn-cnn.ipynb` - Alternate sequence where GNN is processed before CNN.
- `traditional-ml.ipynb` - Baseline results using traditional machine learning classifiers.

## Usage

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Abrar2652/soybean-leaf-disease-classification.git
   cd soybean-leaf-disease-classification
   ```

2. **Download the dataset**:

   - Ensure the **Soybean Diseased Leaf Dataset** is placed in the `data` directory.

3. **Run the Jupyter Notebook**:

   - Open the Jupyter Notebook `seq-cnn-gnn.ipynb` and run the cells to preprocess the data, train the models, and evaluate the results.

## Note on Requirements

All required installations and dependencies are mentioned within each notebook. There is no need to use a separate `requirements.txt` file.


## License

This project is licensed under the **MIT License**.

## Acknowledgments

- The authors of the **Soybean Diseased Leaf Dataset** for providing valuable data for research.
- The open-source community for developing essential machine learning and deep learning tools.

