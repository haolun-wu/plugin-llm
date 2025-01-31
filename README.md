# Code for paper: Logits are All We Need to Adapt Closed Models

This repository contains shell scripts for setting up, evaluating, and performing cross-validation on different models. These scripts help automate the process of training, testing, and comparing various models efficiently.

## Files Overview

### 1. `setup.sh`
This script sets up the necessary environment, installs dependencies, and ensures all required libraries and tools are available before running any model evaluations.

### 2. `evaluate_models.sh`
Runs model evaluation on pre-trained or newly trained models. This script is useful for testing models on a dataset and generating performance metrics.

### 3. `base_model_cross_validation.sh`
Performs cross-validation using the base model. This script is helpful for assessing the performance of the baseline model using standard cross-validation techniques.

### 4. `plugin_model_cross_validation.sh`
Runs cross-validation for a plugin-based model. This script is useful if additional plugins or extensions are used in the model and need validation.

### 5. `weighted_model_cross_validation.sh`
Executes cross-validation using a weighted ensemble model. It helps evaluate models that combine multiple sources with different importance weights.

## Usage

Make sure you have the necessary dependencies installed before running any script. The following steps can be used to execute these scripts:

### 1. Set Up the Environment
```sh
bash setup.sh
```

### 2. Evaluate Models
```sh
bash evaluate_models.sh
```

### 3. Run Cross-Validation
```sh
bash base_model_cross_validation.sh
bash plugin_model_cross_validation.sh
bash weighted_model_cross_validation.sh
```

## Prerequisites
Ensure you have the following dependencies installed:
- Bash (Unix/Linux/macOS)
- Python (if models are implemented in Python)
- Required ML/DL frameworks (TensorFlow, PyTorch, Scikit-learn, etc.)
- Any additional libraries specified in `setup.sh`

