**LLM Project with Hugging Face API**

**Overview :**
This project integrates a Large Language Model (LLM) using the Hugging Face API to interact with a MySQL database. It leverages LangChain for database chaining and Chroma DB for vectorization to handle complex queries. The workflow involves creating embeddings for questions to enhance the LLM's response accuracy.

**Features**

LLM Integration: Utilizing the Hugging Face API to process and respond to SQL questions.
Database Connection: Connection to MySQL database to interact with multiple tables.
LangChain: Creating database chains to handle SQL queries.
Chroma DB: Implementing vectorization for question embeddings to improve LLM performance.
Embeddings Storage: Storing and retrieving question embeddings in Chroma DB for efficient query processing.

**Prerequisites**
Python 3.8 or higher
MySQL database
Hugging Face API key
**Steps**
Clone the repository:

Create a virtual environment and activate it:
 
Install the required packages:

bash
Copy code
pip install -r requirements.txt
Set up environment variables for configuration (see Configuration).


License
This project is licensed under the MIT License. See the LICENSE file for details.

Feel free to open issues or submit pull requests. Your feedback and contributions are highly appreciated!






