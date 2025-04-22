# 🎓 Student Learning Style Classifier

This project aims to classify students based on their learning preferences — **Visual**, **Auditory**, or **Kinesthetic** — using a machine learning model. By analyzing questionnaire scores, the model helps personalize education and adapt teaching strategies to improve learning outcomes.

## 🧠 Problem Statement

Students have unique learning styles, and recognizing them can enhance the educational experience. This project uses machine learning to classify students based on scores in visual, auditory, and kinesthetic dimensions. The output is a predicted learning style that aligns with their preferences.

## 🔍 Methodology

### 1. Dataset

Each record in the dataset contains:

- `visual_score`: Preference for visual learning
- `auditory_score`: Preference for auditory learning
- `kinesthetic_score`: Preference for physical/hands-on learning
- `learning_style`: Actual learning style label

### 2. Preprocessing

- Loaded dataset using **Pandas**
- Extracted features (`X`) and target labels (`y`)
- Split into **80% training** and **20% testing** sets

### 3. Model Used

- **Random Forest Classifier**
- Chosen for its robustness in multi-class classification and ability to reduce overfitting

### 4. Evaluation Metrics

- **Confusion Matrix** (with heatmap)
- **Accuracy**
- **Precision** (weighted)
- **Recall** (weighted)

## 🧪 Results

The model's predictions were evaluated on the test set using standard classification metrics. A confusion matrix heatmap was also plotted for better interpretability.

## 📊 Visualization

A confusion matrix heatmap was generated using **Seaborn** to visualize model performance.

## 📦 Dependencies

- Python 3.x
- pandas
- scikit-learn
- seaborn
- matplotlib

You can install the required libraries using:

bash
pip install pandas scikit-learn seaborn matplotlib




🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/learning-style-classifier.git
cd learning-style-classifier
Make sure the dataset (student_methods.csv) is in the project directory.

Run the Python script (e.g., in Jupyter Notebook or any Python environment).


🧾 References
Dataset: Based on student learning style questionnaire scores, aligned with the VARK model.

Libraries:

Pandas

Scikit-learn

Seaborn

Matplotlib

🙌 Acknowledgements
Developed as an academic project to demonstrate machine learning in education.
