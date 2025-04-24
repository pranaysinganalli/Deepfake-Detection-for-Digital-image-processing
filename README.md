# An efficient video model for Deepfake Detection
### Digital image processing
Project files for the assignment "An efficient video model for Deepfake Detection" under Prof. Geetha S.
This repository contains the code, output of our project as well as the report, base paper, reference papers ans presentation. Read below for more info

### Team

Pranay Singanalli - 22BCE1140

Vertika Singh - 22BCE1148


## 📦 Major Frameworks
- **PyTorch** - For everything related to deep learning
- **Numpy** - For some array manipulation and algebra
- **Matplotlib** - For visualization

## 📚 Dataset Used
We have used a popular DeepFake dataset (referenced within the notebook) for real vs fake classification. It contains a mix of real and manipulated (deepfake) images or frames extracted from videos.

- All the required data will download itself using the `download_and_process_data()` function in the notebook.
- If needed, you can download the processed dataset (e.g., JPEG format frames) from the links provided in the notebook.

## 📖 Referred Papers
All the papers referred to in our project report are listed in the `references/` folder:

- The file names match their reference numbers in the report (e.g., `12.pdf` for reference [12]).
- There is also a folder named `All papers` inside the above folder which contains the additional research papers used during the literature survey (submitted as DA-1).

## 🚀 Steps to Run

### ✅ In Cloud/Kaggle/Colab (Recommended)
- Just run the notebook as-is in **Kaggle** (GPU enabled) or **Google Colab**.
- All necessary packages are installed in the first cell.
- The model will be retrained each time from scratch, so results may vary slightly from the report.

### 🖥️ Local (Linux Required)
- Install the following packages:
  - PyTorch with CUDA support
  - Numpy
  - Pillow
  - Matplotlib
  - Any additional dependencies listed in the notebook’s first cell
- System Requirements:
  - At least **8 GB GPU VRAM**
  - **8 GB RAM**
  - At least **1 GB free disk space**

## 📊 Results
Performance on the test set:
- **Accuracy**: 93.5%
- **Precision**: 91.8%
- **Recall**: 92.7%
- **F1-Score**: 92.2%

## 🖼️ Sample Output
- **Red** = Predicted label
- **Blue** = True label

> *(Include visualizations here if needed)*

---

Feel free to contribute or raise issues!
