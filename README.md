# 🩺 Multiple Disease Prediction Streamlit App

This project is a web-based application that predicts the likelihood of three major diseases—**Diabetes**, **Heart Disease**, and **Parkinson's Disease**—using machine learning models. Built with **Streamlit**, the app offers an interactive interface for users to input medical data and receive real-time predictions.([GitHub][1])

---

## 🚀 Features

* **Multi-Disease Prediction**: Utilizes trained machine learning models to predict:

  * Diabetes
  * Heart Disease
  * Parkinson's Disease
* **Interactive User Interface**: Built with Streamlit for seamless user experience.
* **Real-Time Results**: Provides instant predictions based on user inputs.
* **Pre-trained Models**: Models are pre-trained and saved, ensuring quick responses without the need for retraining.([Streamlit][2], [GitHub][1])

---

## 🛠️ Technologies Used

* **Frontend**: Streamlit
* **Backend**: Python
* **Machine Learning Models**: Trained using scikit-learn
* **Data Handling**: Pandas, NumPy([GitHub][3], [GitHub][4])

---

## 📁 Project Structure

```plaintext
multiple-disease-prediction-streamlit-app-main/
├── .streamlit/                 # Streamlit configuration files
├── colab_files_to_train_models/ # Jupyter notebooks for model training
├── dataset/                    # Datasets used for training
├── saved_models/               # Serialized trained models (.sav files)
├── app.py                      # Main Streamlit application
├── requirements.txt            # Python dependencies
├── bg.jpg                      # Background image for the app
└── README.md                   # Project documentation
```



---

## ⚙️ Getting Started

### Prerequisites

Ensure you have the following installed:

* Python 3.6 or higher
* pip (Python package installer)([GitHub][5])

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Khushi-2409/multiple-disease-prediction-streamlit-app-main.git
   cd multiple-disease-prediction-streamlit-app-main
   ```



2. **Install the required packages**:

   ```bash
   pip install -r requirements.txt
   ```



3. **Run the application**:

   ```bash
   streamlit run app.py
   ```



The app will open in your default web browser at `http://localhost:8501/`.

---

## 🧪 Model Training

The `colab_files_to_train_models/` directory contains Jupyter notebooks used to train the machine learning models for each disease prediction. These notebooks detail the data preprocessing, model training, and evaluation processes.([GitHub][6])

---

## 📊 Datasets

Datasets used for training the models are located in the `dataset/` directory. Each dataset corresponds to a specific disease and includes relevant medical parameters.

---

## 📸 Screenshots

*Include screenshots of the application interface here.*

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

* Inspired by various open-source healthcare projects and the Streamlit community.
* Thanks to the contributors who provided the datasets and initial model frameworks.
