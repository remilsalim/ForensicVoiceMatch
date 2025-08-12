# ForensicVoiceMatch

## Overview
ForensicVoiceMatch is a **digital audio forensics** project designed to match a suspect’s recorded voice sample against call recordings retrieved from a victim's/suspect's device.  
The goal is to verify whether the same individual appears in both the **lab-recorded voice sample** and **mobile phone recordings**, which are suspected to contain incriminating conversations related to a criminal case.

This project uses **open-source audio processing tools** and **AI/ML techniques** for accurate speaker identification.

---

## Project Objective
- Record a **voice sample** of the accused at the lab.
- Analyze and compare it with **three call recordings** obtained from a mobile device.
- Determine whether the voices belong to the **same person**.
- Provide a documented and reproducible workflow for forensic analysis.

---

## Domain
**Digital Forensics (Audio Analysis)**

---

## Tools & Technologies
- **Python** (Data processing & ML model implementation)
- **Jupyter Notebook** (`Audio_Project.ipynb`)
- **Audacity** – Audio editing & preprocessing
- **GoldWave** – Advanced audio processing
- **Open-source APIs** for audio fingerprinting & feature extraction
- **Machine Learning** for voice classification and similarity scoring

---

## Required Data
To run the analysis, the user must have:
- **1 cleaned voice sample** of the suspect (recorded in lab conditions, noise removed).
- **3 separate call recordings** retrieved from the suspect/victim device (preferably in `.wav` format).

---

## Expected Outcome
- A **proof-of-concept (POC)** that demonstrates successful voice matching.
- Detailed **step-by-step execution documentation**.
- A final **forensic analysis report** and **presentation slides**.

---

## Repository Structure
```
ForensicVoiceMatch/
│
├── Audio_Project.ipynb     # Main analysis code
├── data/                   # Audio samples (not included for confidentiality)
├── README.md               # Project documentation
├── requirements.txt        # Python dependencies
└── reports/                # Generated results and documentation
```

---

## Setup & Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/ForensicVoiceMatch.git
   cd ForensicVoiceMatch
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Prepare your audio data**
   - Place **1 cleaned suspect voice sample** and **3 call recordings** inside the `data/` folder.
   - Ensure all files are in `.wav` format.

4. **Run the analysis**
   Open the Jupyter notebook:
   ```bash
   jupyter notebook Audio_Project.ipynb
   ```

---

## Methodology
1. **Audio Preprocessing**
   - Noise reduction
   - Normalization
   - Trimming silence
2. **Feature Extraction**
   - MFCC (Mel-Frequency Cepstral Coefficients)
   - Spectral features
3. **Voice Matching**
   - Similarity scoring
   - Machine learning classification
4. **Result Verification**
   - Statistical confidence
   - Manual forensic review

---


## Confidentiality Notice
This project is based on a **confidential forensic investigation**. Actual audio files are excluded from this repository to protect privacy and legal integrity.
