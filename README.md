# Parkinson's Disease Detection from Voice Analysis

A machine learning project for detecting Parkinson's disease from voice recordings of sustained vowel /a/ pronunciation.

## 🎯 Project Overview

This project implements a lightweight machine learning approach to detect Parkinson's disease from voice characteristics. The system analyzes acoustic features extracted from sustained vowel recordings and uses various ML algorithms to classify patients vs. healthy controls.

### Key Features

- **Lightweight Implementation**: Optimized for small datasets (80-100 samples)
- **Comprehensive Analysis**: Cross-validation, feature importance, detailed evaluation
- **Multiple Models**: Comparison of Random Forest, Logistic Regression, SVM, and more
- **Rich Visualizations**: ROC curves, confusion matrices, feature importance plots
- **Modular Design**: Easy to extend with new features and models
- **Production Ready**: Includes prediction pipeline for new audio files

## 📊 Dataset

The project expects:
- Audio files in WAV format containing sustained vowel /a/ recordings
- Excel file with demographic information (age, sex) and labels (HC/PwPD)
- Sample structure:
  ```
  Demographics_age_sex.xlsx:
  Sample ID                                    | Label | Age | Sex
  AH_545713222-DA13DC3A-F24B-454E-984F-19DF... | PwPD  | 65  | M
  AH_064F_7AB034C9-72E4-438B-A9B3-AD7FDA15...  | HC    | 45  | F
  ```

## 🏗️ Project Structure



## 🚀 Quick Start

### 1. Installation



### 2. Data Preparation

1. Place your WAV files in `data/raw/audio_files/`
2. Place your demographics Excel file at `data/raw/Demographics_age_sex.xlsx`
3. Update paths in `config/