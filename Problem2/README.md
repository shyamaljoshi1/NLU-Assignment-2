# Problem 2: RNN-Based Name Generation

This project implements and compares three different RNN architectures for generating names: Vanilla RNN, Improved BiLSTM, and RNN with Causal Attention.

## Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/shyamaljoshi1/NLU-Assignment-2.git
cd NLU-Assigement-2/Problem2
```

### 2. Run the Notebook
Open and execute **`NLU_Assignment_2.ipynb`** in Jupyter Notebook:
```bash
jupyter notebook NLU_Assignment_2.ipynb
```

Or open it directly in VS Code with the Jupyter extension.

### 3. Execute All Cells
- Click "Run All" or execute cells sequentially
- The notebook will train all three models and generate sample names

## What's Included

- **Vanilla RNN**: Baseline recurrent neural network
- **Improved BiLSTM**: Bidirectional LSTM with auxiliary backward training
- **RNN + Causal Attention**: RNN with attention mechanism for better context awareness

## Output Files
The notebook generates:
- Training loss curves (`loss_curves.png`)
- Model complexity comparison (`param_comparison.png`)
- Evaluation metrics visualization (`evaluation_metrics.png`)
- Generated name samples and statistics
- Summary results (`results_summary_v2.json`)

## Requirements
- Python 3.7+
- PyTorch
- NumPy, Matplotlib

All dependencies are listed in the notebook and will be imported automatically.

