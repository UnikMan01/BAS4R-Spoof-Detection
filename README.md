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

This repository contains baseline experiment notebooks used for evaluating different spoofing conditions included in the BAS4R dataset.

### Channel-based Attacks
- **Channel-based.ipynb**

Experiments for communication channel distortions including:
- GSM Codec Simulation  
- Telephone Transmission  
- VoIP Low-Bitrate Communication  

---

### Effect-based Transformations
- **Effect-based.ipynb**

Voice effect transformations including:
- Echo  
- Monster  
- Robot  

---

### Replay-based Attacks
- **Replay-based.ipynb**

Replay attack simulations including:
- Device Re-recording  
- Distance Replay  
- Speaker-to-Microphone Replay  

---

### Signal Processing Transformations
- **Signal Processing.ipynb**

Digital signal processing manipulations including:
- Pitch Shift  
- Formant Shift  
- Time Stretch  

---

## Installation

Install the required Python libraries using:

```bash
pip install -r requirements.txt
```

---

## Citation

If you use the **BAS4R dataset** or the provided experimental notebooks in your research, please cite the dataset as follows:

Ahmad, Al Arian; Aman, Nakib; Dutta, Durjoy Kumar; Wadud, Md. Abdul.  
**BAS4R: A Multi-Condition Bangla Speech Dataset for Gender-Aware Real and Fake Voice Analysis.**  
Harvard Dataverse, 2026.

DOI: https://doi.org/10.7910/DVN/YVWOAL

### BibTeX

```bibtex
@dataset{ahmad2026bas4r,
  author = {Ahmad, Al Arian and Aman, Nakib and Dutta, Durjoy Kumar and Wadud, Md. Abdul},
  title = {BAS4R: A Multi-Condition Bangla Speech Dataset for Gender-Aware Real and Fake Voice Analysis},
  year = {2026},
  publisher = {Harvard Dataverse},
  doi = {10.7910/DVN/YVWOAL}
}
```

Researchers using the BAS4R dataset are encouraged to cite the dataset DOI and the associated publication to support reproducible research in Bangla speech spoof detection and voice authentication systems.

---

## License

This repository is released under the **MIT License**.
