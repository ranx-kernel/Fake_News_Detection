📰 Fake News Detection
📌 Objective
This project uses Natural Language Processing (NLP) and Machine Learning to classify news articles as Fake or Real.
The system analyzes the text of a news article and predicts whether it belongs to the fake or real news category.
⚠️ Disclaimer: This is a machine-learning classification project. The model's prediction does not prove whether a news article is factually true or false. Its performance depends on the dataset and training process.

🛠️ Technologies Used
- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression
- Matplotlib
- Seaborn
- Gradio
- Google Colab
🔄 Project Workflow
News Dataset
     ↓
Data Preprocessing
     ↓
Combine Title + News Text
     ↓
Train/Test Split
     ↓
TF-IDF Vectorization
     ↓
Logistic Regression
     ↓
Fake / Real Prediction
     ↓
Confidence Score

📊 Dataset
The dataset contains two categories:
- Fake News → Label 0
- Real News → Label 1
The title and text columns are combined to create the input text used for classification.
🤖 Machine Learning Model
TF-IDF
Term Frequency–Inverse Document Frequency (TF-IDF) converts news text into numerical features that can be understood by the machine-learning model.
Logistic Regression
Logistic Regression is used as the classification algorithm to predict:
0 → FAKE
1 → REAL

📈 Evaluation
The project evaluates the model using:
- Accuracy
- Precision
- Recall
- F1-score
- Classification Report
- Confusion Matrix
A confusion matrix is also visualized using Seaborn.
🧪 Example
Input:
Scientists announce a major discovery after years of research.

Possible output:
Prediction: REAL
Confidence: 92.45%

The confidence represents the model's estimated probability, not a guarantee of factual accuracy.
🎨 Gradio Interface
The project includes a simple Gradio interface where users can enter a news article and receive a prediction.
Features
- Enter custom news text
- Predict Fake/Real
- Display prediction confidence
- Easy-to-use interface
📁 Project Structure
11_Fake_News_Detection/
│
├── Fake_News_Detection.ipynb
├── README.md
└── requirements.txt

▶️ How to Run
1. Open the Notebook
Open:
Fake_News_Detection.ipynb

using Google Colab or Jupyter Notebook.
2. Install Dependencies
pip install -r requirements.txt

3. Run the Notebook
Execute the cells in order.
4. Test the Model
Enter your own news text in the Gradio interface.
📦 Requirements
pandas
scikit-learn
matplotlib
seaborn
gradio

🎯 Learning Outcomes
Through this project, you can learn:
- Basic NLP text preprocessing
- TF-IDF feature extraction
- Text classification
- Logistic Regression
- Model evaluation
- Confusion matrices
- Building a simple ML interface using Gradio
🚀 Future Improvements
Possible improvements include:
- Use larger and more diverse datasets
- Try Naive Bayes, SVM, or transformer models
- Add advanced text preprocessing
- Detect misleading headlines
- Add explainable AI features
- Deploy the application online
👩‍💻 Author
Rania R.
Computer Science Engineering | AI/ML
