# 🌟 ScratchVLM 🧠

Welcome to **ScratchVLM** – an advanced Vision-Language Model (VLM) designed to push the boundaries of machine learning research! 🚀

## 📚 Overview

ScratchVLM is a cutting-edge vision-language model designed to understand and generate insights from images and text. This repository contains the implementation of the model, alongside inference scripts and utilities to help you deploy and experiment with ScratchVLM in your own projects.

## 🎯 Features

- 🖼️ **Vision-Language Understanding**: Combine visual and textual information for enhanced machine learning models.
- 🧠 **Advanced Modeling**: Implements state-of-the-art techniques for efficient and effective model training.
- ⚙️ **Flexible Inference**: Easily run inference on your data using our scripts.
- 🛠️ **Utilities Included**: Handy utility scripts to make your workflow smoother.

## 🛠️ Installation

To get started with ScratchVLM, clone this repository and install the necessary dependencies:

```bash
git clone https://github.com/aj-das-research/ScratchVLM.git
cd ScratchVLM
pip install -r requirements.txt
```

## 🚀 Quick Start

### Running Inference

Use the provided `launch_inference.sh` script to run inference with the pre-trained ScratchVLM model:

```bash
bash launch_inference.sh
```

This script will load the model and run inference on the specified input data.

### Customizing Your Model

The `inference.py` script is the core of the inference process. You can modify it to suit your specific needs.

```bash
python inference.py --config your_config.json
```

### Training Your Own Models

You can train your own models using the provided scripts:

- `modeling_gemma.py` 🌟
- `modeling_siglip.py` 📈

Customize the parameters and data paths to start training.

## 📁 File Structure

- `inference.py` – Core script for running inference.
- `launch_inference.sh` – Shell script to simplify inference execution.
- `modeling_gemma.py` – Script for the GEMMA model implementation.
- `modeling_siglip.py` – Script for the SigLip model implementation.
- `processing_paligemma.py` – Data processing script tailored for the GEMMA model.
- `utils.py` – Utility functions to support various tasks.


## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

For questions, feel free to reach out to the repository owner: [aj-das-research](https://github.com/aj-das-research).

