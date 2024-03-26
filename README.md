# CMPE 258 Assignment 2

## Introduction
This project is part of the CMPE 258 course assignments, focused on implementing and training deep learning models. Specifically, this assignment involves working with different datasets and model architectures using PyTorch.

## Prerequisites
Before you can run this project, you need to ensure you have the following installed:
- Python 3.8 or higher
- PyTorch and torchvision
- Visual Studio Code (VSCode)

## Setup
Clone the repository to your local machine using Git:


## Running the Program
You can run the program directly within VSCode using the pre-configured settings in `.vscode/launch.json`. 

### Steps:
1. Open the project folder in VSCode.
2. Go to the 'Run and Debug' sidebar (you can also use the shortcut `Ctrl+Shift+D`).
3. Select the configuration you want to run from the dropdown. There are two main configurations:
   - `Python: Current File` for running the currently open Python file.
   - `Python: MyTorchTrainer` for running the `myTorchTrainer.py` script with specific arguments for training models.
4. Hit the 'Run' button (green play icon) or press `F5` to start execution.

### Modifying Parameters
To run `myTorchTrainer.py` with different parameters, you can modify the `args` array in the `launch.json` file under the `Python: MyTorchTrainer` configuration. Here's a brief overview of the arguments:
- `--data_name`: The name of the dataset to use (e.g., `MNIST`).
- `--data_type`: The type of dataset (e.g., `torchvisiondataset`).
- `--data_path`: Path to the data directory.
- `--model_name`: The name of the model to use (e.g., `mlpmodel1`).
- `--learningratename`: Learning rate scheduling strategy (e.g., `StepLR`).
- `--optimizer`: The optimizer to use for training (e.g., `Adam`).

## Contributors
This project is developed and maintained by [Your Name]. For any queries or contributions, feel free to open an issue or a pull request.

