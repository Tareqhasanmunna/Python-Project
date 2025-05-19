# 📧 Spam Email Detection using Naive Bayes (with GUI)

This project is a simple yet effective spam email detector built using Python. It uses the Naive Bayes algorithm for classification and provides a clean GUI interface for user interaction.

---

## 🚀 Features

- 🧠 **Naive Bayes Model** trained on labeled email data (spam/ham)
- 📂 **Custom Dataset Upload** (CSV format)
- 📬 **Manual Message Check** via GUI
- 📊 **Accuracy Report** and test results display
- 🖥️ **Tkinter-based GUI** in a separate file for better modularity

---

## 🛠️ Technologies Used

- Python
- Scikit-learn
- Pandas
- Tkinter
- Jupyter Notebook

---

## 🧪 How to Run

1. **Clone the repo**
    ```bash
    git clone https://github.com/Tareqhasanmunna/Spam-Email-Detection-Project-using-ML
    cd Spam-Email-Detection-Project-using-ML

    ```

2. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the GUI**
    ```bash
    python gui.py
    ```

---

## 📁 Project Structure

📁 Dataset
   │
   ▼
🧹 Preprocessing
   - Clean text
   - Remove stopwords
   - Convert to lowercase
   - Vectorize (CountVectorizer / TF-IDF)
   │
   ▼
🤖 Model Training
   - Naive Bayes classifier
   - Fit on training data
   │
   ▼
🧪 Model Testing
   - Evaluate with test data
   - Accuracy, precision, recall
   │
   ▼
📤 Output
   - Predict spam or ham
   - GUI displays the result


---

## 📸 Screenshots


### 🖥️ GUI Preview
![GUI Screenshot](https://github.com/Tareqhasanmunna/Python-Project/blob/main/spam%20email%20detection%20gui.png)

---

## 📌 Notes

- Your dataset should have two columns: `label` and `text`
- Labels must be in `spam` / `ham` format for best results
- Model accuracy may vary depending on the dataset quality

---

## 🧑‍💻 Author

**Tareq Hasan**  
📧 tareqprofessional@gmail.com  
🌐 https://bd.linkedin.com/in/tareq-hasan-602b8932b

---

## 📜 License

This project is open-source and free to use for educational purposes.

