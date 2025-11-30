# EEG Foundation Models

Deep learning foundation models for electroencephalography (EEG) signal analysis.

## Overview

This repository contains implementations, tutorials, and tools for working with deep learning models designed for EEG data. The project focuses on building and training neural networks for brain-computer interfaces (BCI), cognitive neuroscience, and clinical applications.

## Getting Started

### Tutorials

Interactive Jupyter notebooks and comprehensive setup guides are available in the [`braindecode/tutorials/`](braindecode/tutorials/) directory:

- **Setup Instructions** - Complete environment setup for macOS/Linux/Windows
- **Simple Training Tutorial** - Basic EEG model training with MNE epochs
- **Advanced Preprocessing** - Using EEGPrep for artifact removal and signal cleaning
- **Verification Tools** - Scripts to validate your installation

See the [tutorials README](braindecode/tutorials/README.md) for detailed setup and usage instructions.

## Key Technologies

- **[Braindecode](https://braindecode.org/)** - Deep learning library for raw EEG signal decoding
- **[MNE-Python](https://mne.tools/)** - EEG/MEG data processing and analysis
- **[PyTorch](https://pytorch.org/)** - Deep learning framework
- **[MOABB](https://moabb.neurotechx.com/)** - Benchmark datasets for BCI algorithms

## Project Structure

```
eeg-foundation-models/
├── braindecode/
│   └── tutorials/          # Interactive tutorials and examples
│       ├── README.md       # Setup and getting started guide
│       ├── requirements-core.txt
│       └── *.ipynb         # Tutorial notebooks
└── README.md              # This file
```

## Contributing

Contributions are welcome! Feel free to add tutorials, models, or documentation improvements.

## Resources

- **Braindecode Documentation:** https://braindecode.org/
- **MNE Documentation:** https://mne.tools/
- **PyTorch Documentation:** https://pytorch.org/docs/
