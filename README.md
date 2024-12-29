Email Spam Classification Application
   -A simple web application built with Streamlit that classifies emails as Spam or Not Spam using a pre-trained Machine Learning model.

#馃殌 Features
   >Classify emails as spam or not spam in real-time.
   >Easy-to-use web interface powered by Streamlit.
   >Built with Machine Learning for accurate predictions.

#馃洜锔� Tech Stack
  Backend: Python
  Frontend: Streamlit
  Machine Learning: Pre-trained model using Scikit-learn
  Data Transformation: CountVectorizer

#馃搨 Project Structure
.
鈹溾攢鈹€ spam123.pkl               # Pre-trained ML model (saved with pickle)
鈹溾攢鈹€ vec123.pkl                # CountVectorizer object (for transforming text)
鈹溾攢鈹€ spamDetector.py                    # Main Streamlit app code
鈹溾攢鈹€ requirements.txt          # Python dependencies
鈹溾攢鈹€ README.md                 # Project documentation
鈹溾攢鈹€SpamDetector.ipynb         # jupyter notebook 

#馃弮鈥嶁檪锔� How to Run
>Clone the repository:
git clone https://github.com/Toletisuresh/AICTE_Spam-Email-Classification-using-NLP-and-Machine-Learning.git

>Navigate to the project directory:
cd AICTE_Spam-Email-Classification-using-NLP-and-Machine-Learning

>Install the required dependencies:
pip install -r requirements.txt

>Run the application:
streamlit run spamDetector.py

>Open your browser at http://localhost:8501 to view the app.

#鉁夛笍 Usage
Enter the email content in the provided text area.
Click the Classify Email button.
The app will display whether the email is spam or not.

#馃幆 Example
Input:
Congratulations! You've won a $1,000 Gift Card. Click here to claim your prize!
Output:
鉂� This is a Spam Email.

#馃 Model Details
Model: Pre-trained classifier (e.g., Naive Bayes, SVM, etc.)
Dataset: Trained on a dataset of labeled emails (e.g., Ham vs Spam emails).

#馃摝 Dependencies
Python 3.10.5
Streamlit
Scikit-learn
Pickle

#馃 Contribution
Thank U,for all the Contributions!

#馃摐 License
This project is licensed under the AICTE License.

馃懆鈥嶐煉� Author
Suresh Toleti
馃摟 sureshtoleti56@gmail.com 
