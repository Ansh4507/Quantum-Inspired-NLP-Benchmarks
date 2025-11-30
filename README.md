# Quantum-Inspired NLP Benchmarks: From QBERT to Wave Interference

## 📌 Project Overview
This project explores the intersection of Quantum Computing and Natural Language Processing (QNLP). It implements and compares **10 different architectures**, ranging from standard Quantum Encodings (Amplitude, Angle) to Variational Quantum Circuits (PQC), and introduces a novel **Multi-Scale Quantum Interference Network (MS-QIN)**.

The goal was to demonstrate that modeling language as **wave functions** and **mixed states** can outperform classical baselines like BERT on complex technical classification tasks.

## 🏆 Key Results (The "Hero" Model)
My proposed method, **MS-QIN**, treats sentences as holographic interference patterns at the word, phrase, and context levels. It achieved State-of-the-Art performance on the dataset.

| Model Architecture | Method | Accuracy | F1-Score |
| :--- | :--- | :--- | :--- |
| **BERT (Baseline)** | Classical | ~82.00% | 0.82 |
| **AE-QBERT** | Amplitude Encoding | 84.38% | 0.84 |
| **DME-QBERT** | Density Matrix (Mixed State) | 86.88% | 0.87 |
| **HPQC-QBERT** | Hybrid Parallel PQC | 86.88% | 0.87 |
| **MS-QIN (Proposed)** | **Multi-Scale Wave Interference** | **91.46%** | **0.91** |

## 🧪 Methodologies Implemented

### 1. Fixed Feature Maps
Using quantum circuits as fixed kernels to map BERT features into high-dimensional Hilbert spaces.
* **Amplitude Encoding:** Leveraged exponential capacity ($2^N$ states).
* **Polar/Complex Encoding:** Utilized complex-valued inputs to double information density.

### 2. Quantum Neural Networks
Trainable variational circuits.
* **Density Matrix Embedding (DME):** Modeled semantic ambiguity using trace-based measurement.
* **Hybrid PQC:** A parallel architecture fusing Classical high-res features with Quantum non-linear features.

### 3. Multi-Scale Quantum Interference Network (MS-QIN)
A novel architecture that moves away from vector geometry entirely.
* **Wave Logic:** Maps words to Amplitude ($r$) and Phase ($\phi$).
* **Interference:** Calculates Constructive/Destructive interference energy.
* **Holographic Pooling:** Applies interference at 3 scales (Word, Phrase, Context) simultaneously.

## 🛠️ Tech Stack
* **Language:** Python
* **Deep Learning:** PyTorch
* **Quantum Computing:** PennyLane
* **NLP:** Hugging Face Transformers (BERT)
* **Data Processing:** Pandas, Scikit-Learn

## 📂 Dataset
The model was trained on a balanced dataset of **2,400 technical questions** across 8 domains (Computer Networks, OS, Mathematics, etc.).

## 🚀 How to Run
1. Open the `.ipynb` file in Google Colab.
2. Upload `questions-data-new.csv` to the runtime.
3. Run the cells to reproduce the experiments for AE-QBERT, HPQC-QBERT, and MS-QIN.
