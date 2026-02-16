# Facial Expression Recognition with CNN-BiLSTM

Emotion detection from facial images using hybrid CNN-BiLSTM architecture with class imbalance handling

## 📋 Table of Contents
- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Author](#author)

## 🎯 Overview

Emotion detection from facial images using hybrid CNN-BiLSTM architecture with class imbalance handling.

This project demonstrates:
- End-to-end machine learning pipeline
- Data preprocessing and feature engineering
- Model training and evaluation
- Results visualization and interpretation

## 🔍 Problem Statement

Facial expression recognition is challenging due to class imbalance (some emotions like sadness and fear are underrepresented) and subtle variations in facial features. This project addresses these challenges using a hybrid deep learning approach.

## 📊 Dataset

**Source:** Facial Expression Recognition (FER) dataset with multiple emotion classes including happiness, anger, sadness, fear, surprise, and neutral

**Note:** The dataset is not included in this repository due to size constraints. Please download it separately from the source mentioned in the notebook or contact the author for access instructions.

## 🔬 Methodology

This project employs the following techniques and models:

- **CNN**
- **Bidirectional LSTM**
- **Data Augmentation**
- **Class Imbalance Handling**
- **Image Preprocessing**

The notebook includes:
- Exploratory Data Analysis (EDA)
- Data preprocessing and cleaning
- Feature engineering and selection
- Model training and hyperparameter tuning
- Performance evaluation and visualization
- Results interpretation

## 📈 Results

Robust emotion classification with improved performance on minority classes

Detailed results, metrics, and visualizations are available in the Jupyter notebook.

## 🚀 Installation

### Prerequisites
- Python 3.8 or higher
- pip package manager
- Jupyter Notebook or JupyterLab

### Setup

1. Clone the repository:
```bash
git clone https://github.com/pradyten/facial-expression-recognition-cnn-bilstm.git
cd facial-expression-recognition-cnn-bilstm
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

4. Download necessary data files (see Dataset section)

## 💻 Usage

1. Launch Jupyter Notebook:
```bash
jupyter notebook
```

2. Open `facial-expression-recognition.ipynb` in the Jupyter interface

3. Run the cells sequentially from top to bottom

4. Modify parameters and experiment with different approaches as needed

**Note:** Some cells may require significant computational resources and time to execute, especially model training sections.

## 📁 Project Structure

```
facial-expression-recognition-cnn-bilstm/
│
├── facial-expression-recognition.ipynb          # Main analysis notebook
├── requirements.txt              # Python dependencies
├── README.md                     # This file
└── .gitignore                    # Git ignore rules
```

## 🛠 Technologies Used

- **Python** - Primary programming language
- **Jupyter Notebook** - Interactive development environment
- **NumPy & Pandas** - Data manipulation and analysis
- **Matplotlib & Seaborn** - Data visualization
- **Scikit-learn** - Machine learning algorithms and utilities
- **TensorFlow/Keras** - Deep learning framework (if applicable)
- Additional libraries as listed in `requirements.txt`

## 👨‍💻 Author

**Pradyumn Tendulkar**

Data Science Graduate Student | ML Engineer

- GitHub: [@pradyten](https://github.com/pradyten)
- LinkedIn: [Pradyumn Tendulkar](https://www.linkedin.com/in/pradyumn-tendulkar)
- Email: [Your Email]

---

⭐ If you found this project helpful, please consider giving it a star!

📝 **Note:** This project was developed as part of my Data Science portfolio. Feel free to fork, modify, and use for learning purposes. For any questions or collaboration opportunities, please reach out!
