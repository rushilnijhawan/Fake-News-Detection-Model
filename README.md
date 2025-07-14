# Fake-News-Detection
📌 Project Overview
In today's digital era, fake news spreads rapidly across social media and news platforms. This project tackles this issue by using a machine learning model trained on real-world news data to predict whether a news article is Real or Fake.

Key steps include:

Data preprocessing and cleaning

TF-IDF vectorization

Model training using Logistic Regression

Evaluation using standard metrics

🛠️ Tech Stack
Python

Jupyter Notebook

Pandas

NumPy

scikit-learn

Matplotlib (optional)

Seaborn (optional)

📂 Project Structure
bash
Copy
Edit
├── fake-news.ipynb        # Jupyter Notebook containing code
├── train.csv              # Dataset (news articles with labels)
├── README.md              # Project overview and instructions
├── requirements.txt       # Dependencies for the project
📊 Dataset
CSV file (train.csv) containing:

News articles (text)

Labels (FAKE or REAL)

🚀 How to Run
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/rushilnijhawan/Fake-News-Detection-Model.git
cd Fake-News-Detection-Model
Install Dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Launch the Notebook:

bash
Copy
Edit
jupyter notebook fake-news.ipynb
Run all cells to train, evaluate, and test the model.

📈 Model Details
Text Vectorization: TF-IDF (Term Frequency-Inverse Document Frequency)

Classifier: Logistic Regression (using scikit-learn)

Evaluation Metrics: Accuracy Score, Confusion Matrix

📑 Results
The model demonstrates strong performance in predicting fake news articles based on the input dataset.

📬 Contributing
Feel free to contribute:

Fork the repository

Create a new branch

Make necessary updates

Submit a Pull Request

📄 License
This project is licensed under the MIT License.

📦 requirements.txt
nginx
pandas
numpy
scikit-learn
jupyter
matplotlib
seaborn
