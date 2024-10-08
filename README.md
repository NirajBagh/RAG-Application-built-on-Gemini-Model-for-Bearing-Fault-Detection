# RAG-Application-built-on-Gemini-Model-for-Bearing-Fault-Detection
This project explores the application of Retrieval-Augmented Generation (RAG) for predictive maintanace and monitoring. The system processes input from the document file and generates a question-and-answer module focused on bearing faults in industrial machine. To design this system, the "Gemini-1.5-pro" language model is utilized to enhance the retrieval and generation capabilities of predictive maintainace and monitoring. The document file is attched in the repository.

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
# Step 04- Create a .env file in the root directory and add your openai credentials as follows:
OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
# Step 05- Run the RAG application using following command:
streamlit run app1.py
