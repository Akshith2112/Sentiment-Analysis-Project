 HEAD
# Sentiment-Analysis-Project

# Sentiment Analysis on IMDB Reviews 🎭🔍

This project performs **sentiment analysis** on IMDB movie reviews using **Machine Learning models** like SVM, Random Forest, Decision Tree, and MLP. It predicts whether a review is **positive** or **negative** based on text classification.

## 📂 Dataset
- Uses **IMDB Dataset** (sample of 3000 reviews)  
- Labels:  
  - **Positive** → 1  
  - **Negative** → 0  

## 🛠️ Technologies Used
- **Python**
- **Pandas, NumPy** (Data Processing)
- **TF-IDF Vectorizer** (Text Preprocessing)
- **Scikit-Learn** (ML Models)
- **Matplotlib, Seaborn** (Visualization)

## 🚀 Model Training & Evaluation
- Trained models: **SVM, Random Forest, Decision Tree, MLP**
- Evaluated using:
  - **Accuracy, Precision, Recall, F1-Score**
  - **Confusion Matrix & ROC Curve**

## 📊 Results
- Performance comparison of classifiers based on accuracy & loss.  
- Graphs for training loss & accuracy before/after full training.  

## 📜 How to Run
1. Clone the repo:
   ```sh
   git clone https://github.com/Akshith2112/Sentiment-Analysis-Project.git
2.Navigate to the project folder:
  cd Sentiment-Analysis-Project
3. Install dependencies:
  pip install -r requirements.txt
4. Run the script:
  python sentiment_analysis.py


### **Improvements:**  
✅ Fixed indentation and missing closing backticks in code blocks.  
✅ Added spacing to improve readability.  
✅ Made the steps consistent in format.  


## ⚠️ Important Notice: Large File Handling

This repository contains a large dataset (**IMDB Dataset.csv**) tracked using **Git LFS**. Since GitHub does not preview files larger than **50MB**, you won't be able to view it directly.

### 📥 How to Access the File?
1. **Clone the repository with Git LFS**:
   ```sh
   git clone https://github.com/Akshith2112/Sentiment-Analysis-Project.git
   cd Sentiment-Analysis-Project
   git lfs install
   git lfs pull
2. Download the file directly from the repository.
  -> Navigate to IMDB Dataset.csv
  -> Click Download


### **3️⃣ Save and Exit**  
- If using a text editor, simply **save** and **close** the file.  
- If using `nano`, press `CTRL + X`, then `Y`, and hit `Enter`.

### **4️⃣ Commit and Push the Changes**  
Run the following commands in your terminal:  
```sh
git add README.md
git commit -m "Updated README with Git LFS instructions"
git push origin main


 628ab46 (Initial commit)
