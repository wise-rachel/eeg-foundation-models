# Braindecode Tutorials

This directory contains interactive Jupyter notebooks for learning braindecode, a deep learning library for EEG analysis.

## Setup

### Creating the Environment

1. Create a Python virtual environment:
   ```bash
   python3 -m venv braindecode_env
   ```

2. Activate the virtual environment:
   - **macOS/Linux:**
     ```bash
     source braindecode_env/bin/activate
     ```
   - **Windows:**
     ```bash
     braindecode_env\Scripts\activate
     ```

3. Install required packages:
   ```bashabout:blank#blocked
   pip install -r requirements-core.txt
   ```

4. Register the Jupyter kernel:
   ```bash
   python -m ipykernel install --user --name=braindecode-tutorial --display-name="Braindecode Tutorial"
   ```

### Key Packages Installed

- **[braindecode](https://braindecode.org/)** - Deep learning library specifically designed for decoding raw EEG signals (dev version with EEGPrep support)
- **[PyTorch](https://pytorch.org/)** - Open-source machine learning framework for building and training neural networks
- **[MNE-Python](https://mne.tools/)** - Comprehensive toolkit for EEG/MEG data processing, visualization, and analysis
- **[MOABB](https://moabb.neurotechx.com/)** - Mother of All BCI Benchmarks - standardized framework for evaluating BCI algorithms with multiple datasets
- **[eegprep](https://github.com/scott-huberty/eegprep)** - Advanced EEG preprocessing pipeline implementing state-of-the-art artifact removal and signal cleaning
- **[Jupyter](https://jupyter.org/)** - Interactive computing environment for creating and sharing computational notebooks
- **[scikit-learn](https://scikit-learn.org/)** - Machine learning library providing classification, regression, and preprocessing utilities
- **[matplotlib](https://matplotlib.org/)** - Comprehensive plotting library for creating static, animated, and interactive visualizations

## Getting Started

1. Open a notebook in your preferred IDE (Positron, VSCode, JupyterLab, etc.)
2. Click on the kernel selector
3. Select your registered kernel (e.g., "Braindecode Tutorial" if you used the command above)
4. Start coding!

The kernel is registered globally, so you can open notebooks from any location.

## Tutorials

### 1. Simple Training with MNE Epochs
**File:** [simple-training-mne-epochs.ipynb](simple-training-mne-epochs.ipynb)

Learn how to:
- Explore available braindecode models
- Create and prepare EEG data with MNE
- Train neural networks using the EEGClassifier wrapper
- Evaluate model performance
- Visualize training results

**Based on:** https://braindecode.org/dev/auto_examples/model_building/plot_basic_training_epochs.html

## Verifying Installation

After installation, activate your environment and run the verification script:

- **macOS/Linux:**
  ```bash
  source braindecode_env/bin/activate
  python verify_installation.py
  ```
- **Windows:**
  ```bash
  braindecode_env\Scripts\activate
  python verify_installation.py
  ```

This will check all critical packages and functionality.

## Troubleshooting

### Kernel not appearing
Re-register the kernel using the activated environment:
```bash
python -m ipykernel install --user --name=braindecode-tutorial --display-name="Braindecode Tutorial"
```

### Import errors
- Make sure you've selected the correct kernel in your IDE
- If using command line, ensure the virtual environment is activated

## Resources

- **Braindecode Documentation:** https://braindecode.org/
- **MNE Documentation:** https://mne.tools/
- **PyTorch Documentation:** https://pytorch.org/docs/

## Contributing

Feel free to add more tutorial notebooks to this directory! Follow the same structure and update this README.
