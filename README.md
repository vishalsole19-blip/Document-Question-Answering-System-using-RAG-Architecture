# Document-Question-Answering-System-using-RAG-Architecture
# About The Project
The Document Question Answering System is a sophisticated tool designed to streamline information retrieval from vast document collections. Built on a foundation of advanced natural language processing techniques, the system features a user-friendly interface powered by Streamlit. Leveraging the LangChain framework and Google Generative AI, it ingests documents, converts them into vector embeddings, and employs the Retrieval augmentation generation(RAG) architecture for accurate question answering. Users can input queries through the intuitive interface, with the system retrieving precise answers based on the document context. With its efficiency, accuracy, and scalability, the system finds applications in research, knowledge management, education, and customer support, representing a significant advancement in information access technology.
# Library Requirements
faiss-cpu
langchain-groq
PyPDF2
langchain_google_genai
langchain
streamlit
python-dotenv
# Getting Started
This will help you understand how you may give instructions on setting up your project locally. To get a local copy up and running follow these simple example steps.
# Installation Steps
# Option 1: Installation from GitHub
Follow these steps to install and set up the project directly from the GitHub repository:

1.Clone the Repository
Open your terminal or command prompt.
Navigate to the directory where you want to install the project.
Run the following command to clone the GitHub repository:
git clone https://github.com/KalyanMurapaka45/Question-Answering-System-using-RAG.git

2.Create a Virtual Environment (Optional but recommended)

It's a good practice to create a virtual environment to manage project dependencies. Run the following command:
conda create -p <Environment_Name> python==<python version> -y

3.Activate the Virtual Environment (Optional)

Activate the virtual environment based on your operating system:
conda activate <Environment_Name>/

4.Install Dependencies

Navigate to the project directory:
cd [project_directory]
Run the following command to install project dependencies:
pip install -r requirements.txt

5.Run the Project

Start the project by running the appropriate command.
streamlit run app.py

6.Access the Project

Open a web browser or the appropriate client to access the project.

# API Key Setup
To use this project, you need an API key from Google Gemini Large Language Model and Groq. Follow these steps to obtain and set up your API key:

Get API Key:

Visit the Provided Links Groq API and Google API.
Follow the instructions to create an account and obtain your API key.
Set Up API Key:

Create a file named .env in the project root.
Add your API key to the .env file:
API_KEY=your_api_key_here
Note: Keep your API key confidential. Do not share it publicly or expose it in your code.

# Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

• Report bugs: If you encounter any bugs, please let us know. Open up an issue and let us know the problem.

• Contribute code: If you are a developer and want to contribute, follow the instructions below to get started!

Fork the Project
1.Create your Feature Branch
2.Commit your Changes
3.Push to the Branch
4.Open a Pull Request

• Suggestions: If you don't want to code but have some awesome ideas, open up an issue explaining some updates or improvements you would like to see!





