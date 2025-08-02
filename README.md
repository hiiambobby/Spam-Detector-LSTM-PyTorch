📦 SMS Spam Classifier (PyTorch)
A simple SMS spam detection model built using PyTorch and an LSTM neural network. The model classifies text messages as either ham (not spam) or spam based on their content.

🧠 Features
Uses an LSTM model to process message sequences

Custom PyTorch Dataset and DataLoader

Handles imbalanced data using class weights or sampling

Saves and resumes training from checkpoints

Supports prediction on new messages

📁 Dataset
The dataset used is SMS Spam Collection, with two columns:

label: ham or spam

message: the text message

🚀 Quick Start
Clone the repo

bash
Copy
Edit
git clone https://github.com/your-username/spam-classifier.git
cd spam-classifier
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run training

bash
Copy
Edit
python train.py
Predict new messages

python
Copy
Edit
predict_message("Free money now!", model, vocab, max_len)
# Output: SPAM
