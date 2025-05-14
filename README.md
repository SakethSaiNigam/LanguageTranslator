🌐 Language Translator

🔍 Overview

The Language Translator is a Python-based application that leverages IBM Watson's Language Translator API to convert text from one language to another. Designed with simplicity and efficiency in mind, this tool offers users a straightforward interface to perform translations seamlessly.

🎯 Features

Multi-language Support: Translate text between various languages supported by IBM Watson.
User-friendly Interface: Interact with the application through a simple web interface built using Flask.
Cloud Integration: Utilizes IBM Watson's robust translation services for accurate and reliable translations.
🛠️ Tech Stack

Programming Language: Python
Web Framework: Flask
API Service: IBM Watson Language Translator
Deployment: Heroku (indicated by the presence of Procfile and setup.sh)
Notebook: Jupyter Notebook for initial development and testing
huggingface.co
📁 Project Structure


LanguageTranslator/
├── app.py
├── requirements.txt
├── setup.sh
├── Procfile
├── Language Translation using IBM Watson.ipynb
└── README.md
app.py: Main Flask application file handling routes and API interactions.
requirements.txt: Lists all Python dependencies required to run the application.
setup.sh: Shell script to set up the environment, especially useful for Heroku deployment.
Procfile: Specifies the commands that are executed by the app on startup (Heroku specific).
Language Translation using IBM Watson.ipynb: Jupyter Notebook demonstrating the translation functionality and serving as a prototype.
GitHub
📈 Project Insights

Commits: 3
Primary Languages:
Jupyter Notebook: 92.2%
Python: 7.1%
License: Not specified
zenodo.org
+11
GitHub
+11
arXiv
+11
🚀 Getting Started

Prerequisites
Python 3.x
IBM Cloud account with access to the Language Translator service
GitHub
Installation
Clone the repository:
git clone https://github.com/SakethSaiNigam/LanguageTranslator.git
cd LanguageTranslator
Set up a virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:
pip install -r requirements.txt
Configure IBM Watson Credentials:
Create an .env file in the root directory.
Add your IBM Watson API key and URL:
DEV Community
GitHub
IBM_API_KEY=your_api_key_here
IBM_URL=your_service_url_here
Run the application:
python app.py
The application will be accessible at http://127.0.0.1:5000/.

🧪 Usage

Navigate to the home page.
Enter the text you wish to translate.
Select the source and target languages.
Click on the "Translate" button to view the translated text.
DEV Community
+1
Devpost - The home for hackathons
+1
ZGY
+8
huggingface.co
+8
Web Machine Learning
+8
zenodo.org

📝 Notes

Ensure that your IBM Watson Language Translator service instance is active and that the API key and URL are correctly configured.
The application currently supports text translation. Additional features like speech-to-text or text-to-speech can be integrated in future iterations.
🤝 Contributing
