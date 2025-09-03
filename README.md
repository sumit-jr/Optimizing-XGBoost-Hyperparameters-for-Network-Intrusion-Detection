# 🔐 Optimizing XGBoost Hyperparameters for Network Intrusion Detection

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Machine Learning](https://img.shields.io/badge/ML-XGBoost-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

This project explores **hyperparameter optimization of the XGBoost algorithm** for building an effective **Network Intrusion Detection System (NIDS)**.  
Using the **UNSW-NB15 dataset**, the study achieves high detection accuracy and robustness against diverse attack types.  

---

## 📊 Overview

- **Objective:** Improve intrusion detection accuracy through systematic tuning of XGBoost hyperparameters.  
- **Dataset:** [UNSW-NB15](https://www.unsw.adfa.edu.au/unsw-canberra-cyber/cybersecurity/ADFA-NB15-Datasets/) (collected by the Australian Centre for Cyber Security).  
- **Methodology:**  
  - Data preprocessing & feature selection  
  - Grid Search & Randomized Search for hyperparameter optimization  
  - Performance evaluation using accuracy, precision, recall, F1-score, and AUROC  

---

## 📂 Repository Structure

```text
├── unsw-nb15.ipynb   # Jupyter notebook with preprocessing, training, and evaluation
├── README.md         # Project documentation
```
## 📈 Results

- **AUROC:** 0.922 – strong separation between attack and normal traffic  
- **Accuracy:** ~92% after tuning  

**Key Improvements:**  
- Better precision and recall balance  
- Reduced false positives compared to baseline models  

---

## 🚀 Usage

### Prerequisites
- Python 3.x  
- Jupyter Notebook  
- Required libraries: `xgboost`, `scikit-learn`, `numpy`, `pandas`, `matplotlib`  

### Run the Notebook
```bash
# Clone repository
git clone https://github.com/sumit-jr/Optimizing-XGBoost-Hyperparameters-for-Network-Intrusion-Detection.git
cd Optimizing-XGBoost-Hyperparameters-for-Network-Intrusion-Detection

# Launch Jupyter Notebook
jupyter notebook unsw-nb15.ipynb
```

## 📚 Dataset Details (UNSW-NB15)

- **Collection Method:** IXIA PerfectStorm tool, simulating realistic normal and malicious traffic  

- **Attack Categories:**  
  - Fuzzers  
  - DoS (Denial of Service)  
  - Backdoors  
  - Exploits  
  - Reconnaissance  
  - Shellcode  
  - Worms, etc.  

- **Features:** 49 (flow-based, basic, time-based statistics) + target label  

👉 More info: [Australian Centre for Cyber Security - UNSW Canberra](https://www.unsw.adfa.edu.au/unsw-canberra-cyber/cybersecurity/ADFA-NB15-Datasets/)  

---

## 📰 Research Publication

- **Title:** Optimizing XGBoost Hyperparameters for Network Intrusion Detection  
- **Conference:** 2024 International Conference on Communication, Computing, Smart Materials and Devices (ICCCSMD)  
- **Conference Location:** Chennai, India  
- **Date of Conference:** 19–20 December 2024  
- **Date Added to IEEE Xplore:** 28 August 2025  
- **Publisher:** IEEE  
- **DOI:** [10.1109/ICCCSMD63546.2024.11015173](https://doi.org/10.1109/ICCCSMD63546.2024.11015173)

---

## 📖 Citation

If you use this work in your research, please cite:

```bibtex
@INPROCEEDINGS{11015173,
  author={Sah, Sumit Prasad and Shahi, Bikram and Nayak, Soumili and Bhardwaj, Ankita and Sah, Biki Kumar},
  booktitle={2024 International Conference on Communication, Computing, Smart Materials and Devices (ICCCSMD)}, 
  title={Optimizing XGBoost Hyperparameters for Network Intrusion Detection}, 
  year={2024},
  pages={1-6},
  publisher={IEEE},
  doi={10.1109/ICCCSMD63546.2024.11015173},
  address={Chennai, India}
}
```

## 📜 License

This project is licensed under the **MIT License**.

