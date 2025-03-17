# Medical Diagnosis with Attention Mechanism

## Overview
This project implements a **Medical Diagnosis System** using an **LSTM model with an Attention Mechanism** in TensorFlow/Keras. The attention mechanism helps the model focus on the most relevant parts of the input when making predictions.

## Features
- Uses **LSTM** for sequential pattern recognition.
- Integrates an **Attention Mechanism** to enhance diagnostic accuracy.
- Employs **word embeddings** for efficient text representation.
- **Binary classification** for medical diagnosis prediction.
- Trains on synthetic data but can be extended to real datasets.

## Requirements
Ensure you have the following dependencies installed:
```bash
pip install tensorflow numpy
```

## Model Architecture
- **Embedding Layer**: Converts input tokens into dense vectors.
- **LSTM Layer**: Captures sequential dependencies in medical data.
- **Attention Layer**: Focuses on important time steps.
- **Dense Output Layer**: Produces a binary classification output.

## Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/ravanasurat/Medical-Diagnosis-with-Attention-Mechanism
cd Medical-Diagnosis-Attention
pip install -r requirements.txt
```

## Usage
Run the training script:
```bash
python train.py
```

## Future Enhancements
- Implement multi-class classification for multiple diseases.
- Integrate a real medical dataset.
- Use **Transformer-based models** for enhanced performance.

## License
This project is open-source under the MIT License.

## Contributing
Feel free to fork the repository and submit pull requests with improvements.

## Contact
For questions or collaborations, reach out via GitHub Issues.
