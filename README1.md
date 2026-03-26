# **🛡️ Spam Mail Detector (Python \+ Machine Learning)**

A Python-based machine learning tool that identifies and filters unsolicited messages (Spam) from legitimate communication (Ham) using Natural Language Processing.

## **📖 Table of Contents**

* [Overview](https://www.google.com/search?q=%23overview)  
* [Key Features](https://www.google.com/search?q=%23key-features)  
* [Tech Stack](https://www.google.com/search?q=%23tech-stack)  
* [Installation](https://www.google.com/search?q=%23installation)  
* [Usage](https://www.google.com/search?q=%23usage)  
* [Project Structure](https://www.google.com/search?q=%23project-structure)  
* [Future Enhancements](https://www.google.com/search?q=%23future-enhancements)  
* [License](https://www.google.com/search?q=%23license)

## **🔎 Overview**

The **Spam Mail Detector** addresses the global challenge of "inbox fatigue" and cybersecurity risks. With over 50% of global mail traffic consisting of spam, this project replaces manual sorting with an intelligent automation layer.

By leveraging **Natural Language Processing (NLP)** and **Logistic Regression**, the system analyzes statistical patterns in message text to instantly classify mail as "Ham" or "Spam," achieving a **96% accuracy rate** that ensures a cleaner, safer, and more efficient digital workspace.

## **🚀 Key Features**

🐍 **Machine Learning Logic**

* **Binary Classification:** Accurately distinguishes between "Ham" (1) and "Spam" (0).  
* **Logistic Regression:** Utilizes a supervised learning algorithm optimized for binary classification tasks.  
* **Evaluation Metrics:** Includes accuracy score checks on both training and testing data to prevent overfitting.

📊 **NLP & Data Processing**

* **TF-IDF Vectorization:** Converts raw text into numerical feature vectors by weighing word importance across the dataset.  
* **Text Pre-processing:** Automatically handles null values and converts text to lowercase for consistent processing.  
* **Stop-Word Removal:** Filters out common English words (e.g., "is", "the") that do not contribute to classification.

## **🛠️ Tech Stack**

**Language:**

* Python 3.x

**Libraries & Modules:**

* scikit-learn (Logistic Regression, TF-IDF Vectorizer, Train-Test Split)  
* pandas (Data manipulation and CSV handling)  
* numpy (Numerical computations and array handling)

**Data Storage:**

* .csv (Comma Separated Values)

## **⚙️ Installation**

### **Prerequisites**

* Python 3.x installed on your machine.  
* A labeled dataset (e.g., mail\_data.csv).

### **Steps**

1. **Clone the repository**  
   Bash  
   git clone https://github.com/SPARSH/Spam-Mail-Detector.git  
   cd spam-mail-detector

2. **(Optional) Create a Virtual Environment**  
   Bash  
   python \-m venv venv  
   \# Windows  
   venv\\Scripts\\activate  
   \# Mac/Linux  
   source venv/bin/activate

3. **Install Dependencies**  
   Bash  
   pip install pandas numpy scikit-learn

## **🏃 Usage**

1. **Prepare Data:** Ensure mail\_data.csv is in the project directory.  
2. **Run the Application:** Execute the main script to train the model and view accuracy:  
   Bash  
   python main.py

3. **Predict New Mail:** Use the built-in predictive system by providing a custom string to the input\_mail list in the script.

## **📂 Project Structure**

Plaintext

spam-mail-detector/  
├── src/  
│   ├── main.py            \# Main script for data loading, training, and testing  
│   ├── feature\_eng.py     \# TF-IDF Vectorization logic  
│   └── model.py           \# Logistic Regression model implementation  
├── data/  
│   └── mail\_data.csv      \# Persistent dataset (CSV format)  
├── requirements.txt       \# Python dependencies  
├── .gitignore  
└── README.md

## **🔮 Future Enhancements**

* \[ \] **GUI Implementation:** Build a desktop interface using Tkinter or PyQt for user-friendly interaction.  
* \[ \] **Real-time API:** Integrate with live email services to filter incoming messages.  
* \[ \] **Advanced Models:** Implement Naive Bayes or Support Vector Machines (SVM) for performance comparison.  
* \[ \] **Data Visualization:** Create charts to visualize the frequency of common spam words.

## **📜 License**

Developed by

**\[25BAI10167\]**

**\[MANURAJ SARWAIYA\]**

---

