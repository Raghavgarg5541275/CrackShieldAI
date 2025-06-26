# CrackShield AI – The Intelligent Password Guardian

**CrackShield AI** is a next-gen password analysis system powered by machine learning. Designed with a focus on cybersecurity and user empowerment, it intelligently evaluates password strength, estimates realistic cracking times using modern attack strategies, and provides strong password suggestions — all through a visually engaging, interactive UI built in a Jupyter Notebook.

---

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `CrackShield AI – The Intelligent Password Guardian.ipynb` | Main notebook with full UI, password analysis, prediction logic, and real-time news integration |
| `data.csv` | Raw password data for model training |
| `passwords_dataset.csv` | Cleaned and labeled password dataset |

---

## 🔧 Features Overview

### ✔ Password Analysis
- Checks for lowercase, uppercase, special characters, and length
- Trained ML model predicts strength: **Weak**, **Medium**, or **Strong**

### ✔ Time to Crack Estimation
Estimates how long it would take to crack the password using:
- **Brute Force** (10 Billion guesses/sec)
- **Dictionary Attack** (1 Million guesses/sec)
- **Hybrid Guessing** (100 Million guesses/sec)

### ✔ Strong Password Suggestions
- Generates **3 intelligent password suggestions**
- Allows optional inclusion of **user-specified custom word**
- Shows strength and time-to-crack for each suggestion
- **Visual side-by-side comparison** with the original password

### ✔ Interactive User Interface
- Built with **IPyWidgets**
- Styled with HTML/CSS for professional appearance
- Real-time user feedback and validations

### ✔ Live Cybersecurity News
- Uses [NewsData.io](https://newsdata.io/) API to fetch current news on:
  - Password leaks
  - Cybersecurity threats
  - Solutions and education

---

## ▶️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/Raghavgarg5541275/CrackShield-AI---The-Intelligent-Password-Guardian.git
cd CrackShield-AI---The-Intelligent-Password-Guardian
```
2. Install Dependencies
```bash
   pip install pandas ipywidgets requests scikit-learn
```
3. Launch Notebook
Open the **.ipynb** file in Jupyter Notebook or JupyterLab and run all cells sequentially.

🎓 Academic Purpose
This project was developed under the AlgoNinjas Program at Bennett University.
It combines:
- Machine Learning
- Cybersecurity Awareness
- UI/UX Best Practices
…to create an educational yet impactful tool.

👤 Developed By

Raghav Garg

B.Tech CSE (Artificial Intelligence)

Bennett University

[LinkedIn](https://linkedin.com/in/raghavgarg5541275)  

[GitHub](https://github.com/Raghavgarg5541275)

⭐ **Contribute or Star**
If you find this project helpful or interesting, don’t forget to star the repo or suggest improvements via pull requests or issues.
