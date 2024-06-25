# CommonLit Readability Model in Jupyter Notebook

This repository has a Jupyter Notebook that uses PyTorch and the RoBERTa transformer to predict how easy it is to read various literary excerpts. These excerpts are taken from the CommonLit Readability Prize dataset.

## Project Structure

- **`commonlit_readability_prize.ipynb`**: The Jupyter Notebook containing all the code for training and evaluating the model, as well as making predictions.
- **`README.md`**: This file, providing an overview and instructions for setting up and running the notebook.
- **`requirements.txt`**: Lists all Python packages required to run the notebook.
- **`commonlitreadabilityprize/`**: Folder containing the datasets (`train.csv`, `test.csv`, and `sample_submission.csv`).

## Setup

### Prerequisites

- Python 3.8 or higher.
- Jupyter Notebook or JupyterLab.

### Installation

1. Clone this repository:
   ```bash
   git clone git@github.com:Furman12/CommonLit-Readability-Prize.git
   cd commonlit-readability-notebook
   ```

2. Install required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the notebook:

1. Start Jupyter Notebook or JupyterLab:
   ```bash
   jupyter notebook
   ```

2. Open `commonlit_readability_prize.ipynb` in the Jupyter interface that opens in your browser.

3. Run the cells in the notebook sequentially to train the model, evaluate it, and make predictions on the test dataset.

## Notebook Details

- **Model Architecture**: Utilizes the 'roberta-base' model for sequence classification.
- **Training and Evaluation**: The notebook includes cells for training the model, evaluating its performance using RMSE, and making predictions.
- **Visualization**: Includes visualizations of training progress and results.


