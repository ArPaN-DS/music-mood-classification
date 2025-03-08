# 🎵 Music Mood Classification 🎶

A machine learning project that classifies music into different moods using **acoustic features** and **Random Forest Classifier**.

## 📅 Project Overview
- **Dataset**: 300 training samples, 100 test samples
- **Features**: Energy-based, MFCCs, Tempo, Fluctuation
- **Model**: **RandomForestClassifier**
- **Validation Accuracy**: **83.33%**
- **Predictions saved in `final.csv`**

## 📁 Dataset Columns
| Column Name             | Description |
|-------------------------|-------------|
| `Class`                 | 🎯 **Target Label** (Music Mood) |
| `_RMSenergy_Mean`       | 🔊 RMS Energy |
| `_Lowenergy_Mean`       | 🔈 Low Energy Feature |
| `_Fluctuation_Mean`     | 🎶 Measures fluctuations in energy levels |
| `_Tempo_Mean`           | 🎼 Tempo (beats per minute) |
| `_MFCC_Mean_1` to `_MFCC_Mean_n` | 🎵 **MFCCs** - Frequency-based sound patterns |

## 🛠 Technologies Used
- Python 🐍
- Pandas & NumPy 🔢
- Scikit-learn 🤖
- StandardScaler for Feature Scaling
- RandomForest for Classification

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone (https://github.com/ArPaN-DS/music-mood-classification)
   ```
2. Navigate to the project folder:
   ```bash
   cd music-mood-classification
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run Jupyter Notebook and execute `music-mood-classification.ipynb`.

## 👤 Author
👤 **Arpan Majumdar**  
👉 [GitHub Profile](https://github.com/ArPaN-DS)

