# BAS4R Spoof Detection

This repository provides baseline training and evaluation notebooks for the **BAS4R speech spoofing dataset**, a multi-condition Bangla speech dataset designed for gender-aware real and fake voice analysis.

---

## Dataset

The BAS4R dataset is publicly available through the Harvard Dataverse repository:

**DOI:**  
https://doi.org/10.7910/DVN/YVWOAL

Harvard Dataverse ensures long-term preservation, open access, and proper citation of the dataset for reproducible research.

---

## Repository Structure

This repository contains baseline experiment notebooks used for evaluating different spoofing conditions.

### Channel-based Attacks
- **Channel-based.ipynb**  
Experiments for communication channel distortions including:
- GSM Codec Simulation  
- Telephone Transmission  
- VoIP Low-Bitrate Communication  

### Effect-based Transformations
- **Effect-based.ipynb**  
Voice effect transformations including:
- Echo  
- Monster  
- Robot  

### Replay-based Attacks
- **Replay-based.ipynb**  
Replay attack simulations including:
- Device Re-recording  
- Distance Replay  
- Speaker-to-Microphone Replay  

### Signal Processing Transformations
- **Signal Processing.ipynb**  
Digital signal processing manipulations including:
- Pitch Shift  
- Formant Shift  
- Time Stretch  

---

## Installation

Install required Python libraries using:

```bash
pip install -r requirements.txt
