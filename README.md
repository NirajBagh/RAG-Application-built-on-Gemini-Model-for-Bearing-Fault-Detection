# RAG-Application-for-Fault Detection
This project explores the application of Retrieval-Augmented Generation (RAG) for bearing fault detection in industrial machines. The system processes input from document file and generates a question-and-answer module focused on machine bearing faults.To design this system, Gemini pro model is utilized to enhance the retrieval and generation capabilities for fault detection. The document file is attched in the repository.

# How to run?
# Steps:
Clone the repository
https://github.com/NirajBagh/RAG-Application-built-on-Gemini-Model-for-Bearing-Fault-Detection.git
# STEP 01- Create virtual environment after opening the repository in VS studio
py -m venv venv 
# STEP 02- Activate the enviroment
.\venv\Scripts\activate
# STEP 03- install the requirements
pip install -r requirements.txt
# Step 04- Create a .env file in the root directory and add your Google credentials as follows:
GOOGLE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
# Step 05- Run the Ipython Notebook:

