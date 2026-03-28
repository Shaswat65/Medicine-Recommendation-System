# Medicine-Recommendation-System (AI Powered)
Overview

The Medicine Recommendation System is an AI-driven web application that suggests medicines based on user symptoms. It combines Machine Learning + Generative AI (Gemini) with a dataset to provide structured, easy-to-understand medical recommendations.

This project demonstrates the integration of Flask, AI models, and real-world healthcare datasets into a practical application.

Key Features
AI-powered recommendations using Google Gemini
User-friendly web interface (Flask)

Provides:
Medicine names
Dosage details

Explanation
1) Uses dataset for contextual understanding
2) Clean formatted output using Markdown → HTML
3) Fast and interactive response system

Tech Stack
1) Frontend: HTML, CSS (Flask Templates)
2) Backend: Flask (Python)
3) AI Model: Google Gemini API
4) Data Processing: Pandas
5) Other Tools: Markdown, CSV dataset

Project Structure

📁 Medicine-Recommendation-System

│── app.py

│── api.txt

│── combined_output.csv

│── templates/

│    ├── index.html

│    └── result.html

│── static/ (optional)

│── README.md

Dataset Information
The file combined_output.csv is the main dataset used by the system.
It is created as a culmination (merged result) of multiple individual CSV files.
These individual datasets were combined to:
 -Improve data coverage
 -Provide better context to the AI model
 -Enhance recommendation quality

Installation & Setup
1. Clone Repository
git clone https://github.com/your-username/medicine-recommendation-system.git
cd medicine-recommendation-system
2. Install Dependencies
pip install flask pandas google-generativeai markdown
3. Setup API Key
Create a file: api.txt
Paste your Google Gemini API Key inside it
Run the Project
python app.py

Open in browser:

http://127.0.0.1:5000/

How to Use
Enter symptoms (e.g., fever, cough, headache)
Submit the form
View:
Recommended medicines
Dosage instructions
Explanation

Working Principle
1) Load dataset (combined_output.csv)
2) Accept user symptoms via web form
3) Generate structured prompt for AI
4) Send request to Gemini model
5) Convert Markdown → HTML
6) Display results in browser

Disclaimer

This project is for educational purposes only.
It should NOT be used as a substitute for professional medical advice.
Always consult a doctor before taking any medication.

Future Enhancements
1) Integrate advanced ML models
2) Build mobile app version
3) Add patient history tracking
4) Deploy on cloud (AWS / Render / Vercel)
5) Add symptom auto-suggestions

Contributing

Contributions are welcome!
Feel free to fork the repository and submit pull requests.

License

This project is licensed under the MIT License.

Author

Shaswat Behera
