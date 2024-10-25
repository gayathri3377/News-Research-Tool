# News Research Tool 📈

This is a web application designed to assist users in researching news articles by allowing them to input URLs, process the content, and ask questions about the articles. Utilizing advanced language models, the tool generates answers based on the information contained in the provided URLs.

## Features

- **Input URLs**: Users can input up to three news article URLs for processing.
- **Data Processing**: The application loads and processes the content of the articles.
- **Query Functionality**: Users can ask questions about the content, and the bot provides relevant answers.
- **Source Attribution**: The bot displays sources for the answers provided.

## Technologies Used

- **Streamlit**: For creating the web application interface.
- **LangChain**: For handling language model interactions and document processing.
- **OpenAI API**: For language model embeddings and responses.
- **FAISS**: For efficient similarity search and retrieval of embeddings.
- **Python**: The primary programming language used for the project.

## Installation

To run this project locally, follow these steps:

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

### Steps

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd news-research-tool
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up environment variables:
   - Create a `.env` file in the root directory and add your OpenAI API key:
     ```env
     OPENAI_API_KEY=your_openai_api_key
     ```

4. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

5. Open your web browser and navigate to `http://localhost:8501` to access the application.

## Usage

1. Input up to three URLs of news articles in the sidebar.
2. Click the **"Process URLs"** button to load and process the articles.
3. Enter your question in the provided text input field.
4. The bot will return an answer along with the sources for the information.

## Error Handling

- Ensure that the URLs entered are valid and accessible. The application currently does not include extensive error handling for URL loading failures.
- If you encounter issues, check the console output for error messages.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please fork the repository and submit a pull request. 

### Guidelines
- Please ensure that your code adheres to the existing coding style.
- Add tests for any new features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Streamlit](https://streamlit.io/)
- [LangChain](https://langchain.com/)
- [OpenAI](https://openai.com/)
- [FAISS](https://faiss.ai/)

