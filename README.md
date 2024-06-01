# Stock Prediction Using LSTM and Mamba Model

This repository contains the code and resources for comparing the effectiveness of two advanced models, the Mamba Model and Long Short-Term Memory (LSTM) networks, for stock trading prediction. The comparison is based on their architecture, performance, resource usage, and suitability for capturing long-term dependencies in sequential data.

## Repository Structure

- **LSTM_Model.ipynb**: Implementation of the LSTM model for stock prediction.
- **Mamba_Model.ipynb**: Implementation of the Mamba model for stock prediction.
- **COMPARE.ipynb**: Comparison of the performances of the LSTM and Mamba models, including metrics like RMSE, GPU/CPU utilization, and training times.
- **Mamba Model vs LSTM.pptx**: PowerPoint presentation used in class to present the project.
- **Final_Report.pdf**: Comprehensive report detailing the project's objectives, methodologies, results, and conclusions.

## Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Necessary Python libraries: PyTorch, NumPy, Pandas, Matplotlib

You can install the required libraries using pip:

```bash
pip install torch numpy pandas matplotlib
```

### Running the Notebooks

1. **LSTM_Model.ipynb**: Open this notebook in Jupyter and run all cells to train and evaluate the LSTM model for stock prediction.
2. **Mamba_Model.ipynb**: Open this notebook in Jupyter and run all cells to train and evaluate the Mamba model for stock prediction.
3. **COMPARE.ipynb**: Open this notebook in Jupyter and run all cells to compare the performance of the LSTM and Mamba models. This notebook provides detailed analysis and visualizations of the models' performance, resource utilization, and training times.

## Project Overview

Predicting stock prices is a challenging task due to the inherent complexity and volatility of financial markets. Accurate predictions are crucial for traders and investors, and the rise of machine learning techniques has opened new avenues for improving prediction accuracy.

### Mamba Model

- **Architecture**: Utilizes Residual Blocks with selective scan mechanisms for efficient computation.
- **Parameters**: 98,112
- **Performance**: Test RMSE of 0.0323
- **Features**: Innovative architecture aimed at capturing long-range dependencies in sequential data.

### LSTM Model

- **Architecture**: Features memory cells with input, forget, and output gates.
- **Parameters**: 173,851
- **Performance**: Test RMSE of 0.1939
- **Features**: Well-known for its capability to capture long-term dependencies in time-series data.

### Comparison Highlights

- **Model Architecture**: Mamba's Residual Blocks vs. LSTM's recurrent layers with gates.
- **Dependency Handling**: Mamba's potential for long-range dependencies vs. LSTM's established memory retention.
- **Resource Requirements**: Both models have similar memory usage, with Mamba showing higher GPU utilization.
- **Complexity**: Mamba's innovative but complex architecture vs. LSTM's well-understood framework.
- **Practical Applicability**: Mamba for intricate dependency capture; LSTM for versatility.

## Results and Conclusion

The Mamba Model demonstrated better performance and predictive accuracy in stock market prediction tasks compared to the traditional LSTM model, with a more efficient use of parameters and higher GPU utilization indicating more intensive computations. This suggests that the Mamba model could be a more resource-efficient option for stock market prediction tasks.

## Authors

- Avihai Giuili - avigiuili@mail.tau.ac.il
- Omer Bahary - omerbahary@mail.tau.ac.il
- Almog Cohen - almogc1@mail.tau.ac.il

## Acknowledgments

Special thanks to our instructors and colleagues who provided valuable feedback and support throughout this project.
