# Speech Project

## 📌 Project Overview
This project focuses on the transcription component of a code-switched isiZulu dataset. The goal is to analyze and benchmark speech-to-text models for better performance in real-world applications.

## 📂 Folder Structure
```
speech_project/
│── data/
│   ├── recordings/       # Audio files
│   ├── transcriptions.csv  # Transcription dataset
│── src/
│   ├── eda.py             # EDA script
│   ├── utils.py           # Utility functions
│── notebooks/
│   ├── eda.ipynb          # Optional Jupyter notebook for visualization
│── requirements.txt        # Dependencies
│── Dockerfile              # Docker setup
│── README.md               # Instructions
```

## 🚀 Getting Started
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/melatdest/transcription-lesseto.git
cd speech_project
```

### 2️⃣ Set Up the Environment
It is recommended to use a virtual environment:
```bash
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate     # On Windows
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run Exploratory Data Analysis (EDA)
```bash
python src/eda.py
```

### 5️⃣ Run in Jupyter Notebook (Optional)
```bash
jupyter notebook notebooks/eda.ipynb
```

## 🛠 Model Benchmarking
This project benchmarks **Whisper-Small** and **Wav2Vec2** for speech-to-text performance. The key evaluation metrics are:
- **Character Error Rate (CER)**
- **Word Error Rate (WER)**
- **Other relevant performance metrics**

## 🔍 Error Analysis
For the best-performing model, an in-depth error analysis is performed, including:
- **Visualization techniques**
- **Explainability tools**
- **Human-in-the-loop evaluation**

## 📝 Recommendations
Based on findings from EDA and error analysis, suggestions for model improvement will be provided.

## 📦 Running with Docker (Optional)
You can run this project inside a Docker container:
```bash
docker build -t speech_project .
docker run -it speech_project
```

## 👥 Contributors
- **Melat Desta** 

## 📜 License
This project is licensed under the MIT License.

