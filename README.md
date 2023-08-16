# Creating-a-QA-interface-chatbot-app-that-answers-the-user-questions-from-the-uploaded-pdf-file
A Question Answer type Chatbot interface app is created so that the bot can answer questions from a uploaded pdf file.
**1.TITLE:**

- Creating a Question-Answer interface chatbot app to get answers to the questions related to the uploaded pdf document.

**2.DESCRIPTION:**

- This web application allows users to upload a PDF document, ask questions about its content, and receive answers through a user-friendly web interface.

**3.OVERVIEW:**

- This project involves the development of a web application that utilizes a combination of language models, document processing, and retrieval techniques to enable users to ask questions about the content of uploaded PDF file.
- The app is built using Python and Panel, and it leverages various libraries including langchain, OpenAI, chromadb, tiktoken, pypdf, and panel for the different aspects of the application.

**4.INSTALLATION:**

- Use the following command to install the required dependencies:

"pip install langchain openai chromadb tiktoken pypdf panel"

**5.FEATURES:**

- Upload a PDF document: Users can upload a PDF file through the web interface.
- Enter questions: Users can type in questions they want to ask about the content of the uploaded PDF.
- Process and answer: The app processes the questions and provides answers based on the content of the PDF document.

**6.RUNNING THE APP:**

- Clone this repository to your local machine.
- Navigate to the directory where you've saved the `app.py` file using the terminal.
- Run the following command to launch the web app:

"panel serve app.py --port 5000"

- Open a web browser and go to "[http://localhost:5000/app](http://localhost:5000/app)" to access the web app.

**7.USAGE:**

- Upload a PDF file by clicking the "Choose File" button.
- Enter your OpenAI API key in the provided field. You can get an API key from OpenAI ("[https://platform.openai.com/account](https://platform.openai.com/account)").
- Type your question in the text box provided.
- Click the "Run" button to get the answer.The code provides an interactive interface for users to ask questions. Users can type their queries, and the chatbot responds with relevant answers.

**8.ADVANCED SETTINGS:**

- The app also provides advanced settings that allow you to configure the behavior of the question-answering process.
- Number of relevant chunks: Adjust the number of relevant document chunks considered for answering.
- Chain type: Choose from different chain types such as 'stuff', 'map\_reduce', 'refine', and 'map\_rerank' to influence the retrieval process.

**9. ACKNOWLEDGEMENTS:**

- This project utilizes various open-source libraries and technologies, including Panel, langchain, OpenAI, and more. Special thanks to the developers of these tools for making this project possible.

**10. LICENSE:**

- This project is licensed under the MIT LICENSE.

**11. CONTACT INFORMATION:**

For any questions or feedback, please contact:

Name- Niket Virendra Patil

Email- pniket7@gmail.com
