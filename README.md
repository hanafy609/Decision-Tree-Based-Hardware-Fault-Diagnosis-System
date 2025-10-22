# 🧠 DiagnoTree – Intelligent Hardware Fault Detection System

## 📘 Overview
**DiagnoTree** is a machine learning–based system designed to **detect and classify computer hardware faults** using decision tree algorithms.  
The model analyzes system indicators such as **voltage stability**, **RAM errors**, and **CPU temperature** to predict possible hardware failures like **PSU**, **RAM**, or **CPU** faults.  

This project demonstrates how **AI-driven diagnostics** can help identify and prevent hardware malfunctions before they lead to major system failures.  

---

## ⚙️ Features
- ✅ Hardware fault detection using **Decision Tree Classifier**
- 🧩 Supports multi-class classification (PSU, RAM, CPU, CPU+RAM)
- 📊 Visualizes the trained decision tree for better interpretability
- 📈 Evaluates model accuracy and confusion matrix
- 💡 Simple dataset for demonstration and educational use

---

## 🧰 Technologies Used
- **Python 3.x**
- **pandas** – data manipulation
- **scikit-learn** – model training and evaluation
- **matplotlib** – visualization
- **NumPy** – data processing

---

## 📂 Project Structure
```
📁 DiagnoTree
│
├── discerete project code.ipynb     # Main Jupyter Notebook
├── README.md                        # Project documentation
├── requirements.txt                 # Python dependencies (optional)
└── outputs/                         # Optional: tree plot or results
```

---

## 🧪 How It Works
1. **Dataset Creation:**  
   The dataset includes features like:  
   - `Voltage_Stable`  
   - `RAM_Error`  
   - `CPU_Overheat`  
   - `Fault_Type` (target label)  

2. **Model Training:**  
   - Splits data into training (70%) and testing (30%) sets.  
   - Trains a **DecisionTreeClassifier** using the **entropy criterion**.  

3. **Evaluation:**  
   - Tests the model on unseen data.  
   - Displays **accuracy score** and **confusion matrix**.  
   - Visualizes the **decision tree** for interpretability.  

---

## 🚀 How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/DiagnoTree.git
   cd DiagnoTree
   ```
2. Install dependencies:  
   ```bash
   pip install pandas scikit-learn matplotlib
   ```
3. Run the notebook:  
   ```bash
   jupyter notebook "disceret project code.ipynb"
   ```
4. View outputs and modify dataset values to test fault detection behavior.  

---

## 📈 Example Output
```
Accuracy: 0.85
Confusion Matrix:
[[2 0 0]
 [0 1 0]
 [0 0 1]]
```
*(Values shown for demonstration purposes)*  

---

## 🧭 Future Improvements
- Integrate larger and real hardware monitoring datasets  
- Add neural network models for deeper analysis  
- Build a user-friendly GUI for real-time diagnostics  
- Deploy as a REST API for system monitoring tools  

---

## 👨‍💻 Author
**Hanafi**  
Bachelor in Computer Systems Engineering  
October University for Modern Sciences & Arts (MSA)
