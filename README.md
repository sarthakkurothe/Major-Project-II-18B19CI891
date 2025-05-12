
# 🧠 Integrative Multimodal Analysis for Schizophrenia Cause Identification

## 📝 Project Description

Schizophrenia is a complex mental disorder affecting perception, cognition, and behavior. Despite extensive research, its underlying causes remain unclear due to the limitations of unimodal analyses. This project addresses that gap by implementing a **multimodal deep learning framework** integrating **video, audio, and textual** data from patient interviews to identify potential markers and causes of schizophrenia. Through advanced techniques like **transformers, multimodal fusion (mGMU), and NLP**, we aim to improve diagnosis accuracy and enable personalized treatment approaches.

## 📂 Folder Structure

```
.
├── G27.pptx                  # Presentation for Project
├── Dataset_unified.ipynb     # Preparing unified dataset (audio, video, text)
├── Major_1.ipynb             # Outputs for textual data
├── BERT_Transcripts.ipynb    # Outputs for video and audio datasets
├── G27.pdf                   # Documentation and reference papers
├── README.md                 # Project overview (this file)
└── requirements.txt          # Required dependencies
```

## 💡 Source Code Overview

- **Video Processing**: Uses OpenCV and Mediapipe to extract facial gestures, gaze, and expressions.
- **Audio Processing**: Uses Librosa to extract MFCCs, pitch, pause patterns; includes noise reduction.
- **Text Processing**: NLP-based techniques for sentiment analysis, coherence, and keyword extraction.
- **Multimodal Integration**: A unified dataset is created using timestamp-based alignment.
- **Model Architecture**: A transformer-based model integrated with a **Gated Multimodal Unit (mGMU)** processes the synchronized data for classification and pattern recognition.

## 📚 Documentation

- **Model Architecture**: See `G27.pdf`
- **Data Pipeline**: See `G27.pdf`
- **References**: Listed in the final section of this README and available in `See G27.pdf`

## ⚙️ Installation Instructions

```bash
# Clone the repository
git clone https://github.com/sarthakkurothe/Major-Project-II-18B19CI891.git
cd Major-Project-II-18B19CI891-main

# Set up a virtual environment
python -m venv venv
source venv/bin/activate  
venv\Scripts\activate   

# Install dependencies
pip install -r requirements.txt
```

## 📹 5-Minute Video Demonstration

🎥 [Watch Demo Video]([https://www.loom.com/share/62c99faf528541daa45376383d5cbe9d?sid=843b0766-ba6c-4e35-9724-42c587ae9ebf])  
> This video walks through the project's goals, methodology, demo results, and key findings. It includes a high-level overview of the transformer-based multimodal framework and showcases the data pipeline, visual outputs, and model predictions.

## 🧪 Additional Features

### ✅ Project Board & Issues
- We used GitHub Projects to plan milestones and track progress.
- All bugs, enhancements, and discussions are tracked under [GitHub Issues](https://github.com/your-repo/issues).

### 🔬 Unit Tests & Results
- Basic unit tests are provided for preprocessing modules using `pytest`.
- Evaluation results (accuracy, precision, recall, F1-score) are included in the `/results` directory.

## 🔮 Future Work

- Train the model on extended datasets including EEG/fMRI.
- Apply one-shot learning for better generalization on small datasets.
- Deploy as a clinical support tool via a web/mobile app for real-time diagnostics.

## 👥 Team & Contributions

- **Sarthak Kurothe** (211420) – Audio & Text Processing, Model Implementation 
- **Shivansh Kushwaha** (211308) – Video Processing, Experimental Evaluation

**Supervisor**: Dr. Kushal Kanwar (Assistant Professor, CSE, JUIT)

## 📖 References

A detailed list of all academic references used in the project is available in the [Presentation Appendix](./docs/references.bib) and includes works such as:

1. Premananth et al., *Interspeech*, 2024  
2. Göker, SpringerLink, 2023  
3. Chuang et al., *IEEE Transactions on Neural Systems*, 2023  
... *(and more, see presentation)*
