🔧 Tool Wear Prediction using LSTM
This is a Streamlit web application that predicts the condition of a CNC machine tool based on various machining parameters using a pre-trained LSTM deep learning model.

<br>
📌 Features
Predicts:

🛠 Tool Condition – Worn / Unworn / Damaged

🔧 Machining Finalization – Yes / No

👁️ Visual Inspection Outcome – Pass / Fail

Accepts 13 input parameters from the user

Scales input and reshapes data for LSTM time-series model

Beautiful UI with a background image and sidebar input panel

<br>
🧠 Technologies Used
Python

Streamlit

TensorFlow / Keras (LSTM model)

Scikit-learn (Scaler)

Numpy & Pickle

<br>
🗂️ Folder Structure
bash
Copy
Edit
📁 final_project/
│
├── app.py                # Main Streamlit app file
├── tool_wear_model.h5    # Trained LSTM model
├── scaler.pkl            # Scaler for preprocessing input
├── cnc_bg.jpg            # Background image
├── requirements.txt      # Python dependencies
└── README.md             # This file
<br>
🚀 How to Run Locally
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/tool-wear-prediction.git
cd tool-wear-prediction
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the Streamlit app

bash
Copy
Edit
streamlit run app.py

