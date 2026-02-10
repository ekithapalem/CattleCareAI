# **CattleCareAI**  
AI & NLP-based Disease Detection System for Dairy Cattle

##Project Type 
Group Academic project

## **Overview**
CattleCareAI is an AI and NLP-driven system designed to predict diseases in dairy cattle based on symptoms provided by farmers. It utilizes voice recognition, machine learning, and natural language processing to provide a user-friendly and accurate platform for diagnosing cattle diseases and suggesting treatments.

### **Key Features**
- **Symptom Input**: Farmers can input symptoms through text or voice commands.
- **NLP Processing**: The system uses natural language processing (NLP) to understand symptoms and classify them for disease prediction.
- **Machine Learning Model**: A trained machine learning model predicts potential diseases based on input symptoms.
- **Disease Suggestions**: Provides a list of potential diseases with confidence scores and recommended actions for treatment.
- **Multilingual Support**: Supports multiple languages to enhance accessibility for farmers.

 ## My Contribution
- Understood project requirements and problem statement
- Assisted in documentation and report preparation
- Reviewed dataset structure and overall project flow
- Supported result interpretation and team coordination

## **Tech Stack**
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask (Python)
- **Machine Learning**: Scikit-learn, RandomForest, Transformers (Hugging Face)
- **Speech Recognition**: Google SpeechRecognition API (Python)
- **Database**: SQLite/PostgreSQL (depending on your preference)
- **Deployment**: Docker/Heroku/AWS (optional)

## **Installation**
To set up the project locally, follow these steps:

### **1. Clone the Repository**
```bash
git clone https://github.com/yourusername/CattleCareAI.git
cd CattleCareAI
```

### **2. Install Dependencies**
Ensure that you have Python 3.x installed. Install the required libraries by running:

```bash
pip install -r requirements.txt
```

### **3. Train the Machine Learning Model**
Prepare your dataset and train the disease prediction model. You can customize the dataset for cattle diseases. Example:

```bash
python train_model.py
```

### **4. Run the Flask App**
After training the model, run the Flask app to start the web server:

```bash
python app.py
```

The app will run at `http://127.0.0.1:5000/`.

### **5. Testing Voice Input**
To test voice recognition, upload a `.wav` audio file through the interface or use a microphone to input symptoms.

## **Usage**
1. Visit the home page of the web app.
2. Enter symptoms in text form or record voice input.
3. Click "Predict Disease" to get predictions with confidence scores.
4. Follow the treatment recommendations provided by the system.

## **Project Structure**
```
CattleCareAI/
│
├── app.py                    # Main Flask application
├── model.py                  # Machine learning model for disease prediction
├── static/                   # Static files (CSS, JS)
├── templates/                # HTML files
├── train_model.py            # Script to train the disease prediction model
├── requirements.txt          # Python dependencies
└── README.md                 # Project README file
```

## **Contributing**
Feel free to fork this repository and contribute by submitting pull requests. For major changes, please open an issue to discuss what you'd like to change.

## **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

You can customize this template based on your project specifics and add any additional details as needed.

## Credits
This project was developed as a group academic project with team members.
Original implementation belongs to the respective contributors.
