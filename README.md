# Emotion Detection using Image Data

## Overview
This project focuses on emotion detection using images. It preprocesses image data, converts them to grayscale, resizes them to 48x48 pixels, and prepares them for further analysis.

## Features
- Downloads an emotion dataset from Google Drive.
- Extracts the dataset automatically.
- Processes images to a standard format for machine learning applications.
- Splits data into training and validation sets.

## Installation
### Prerequisites
Ensure you have Python installed along with the following dependencies:
```bash
pip install numpy opencv-python matplotlib gdown
```

### Running the Project
1. Clone the repository or download the script.
2. Run the Jupyter Notebook (`main.ipynb`).

## Dataset
The dataset is downloaded from Google Drive using `gdown`. The ZIP file contains images categorized into different emotions.

## File Structure
```
├── main.ipynb          # Jupyter Notebook with code implementation
├── emotion/            # Extracted dataset directory
│   ├── train/          # Training images
│   ├── validation/     # Validation images
```

## Usage
This notebook prepares the data for machine learning models by preprocessing the images. Further steps can include training a CNN or other ML models for emotion classification.

## License
This project is for educational purposes. Ensure you have permission to use the dataset if required.

