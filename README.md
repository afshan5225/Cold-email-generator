# Cold Email Generator

## Overview
The Cold Email Generator is a Streamlit application designed to create personalized cold emails by scraping job listings from a specified URL. By leveraging a language model, the application extracts relevant job information and generates tailored emails for business outreach.

## Features
- Input a URL to scrape job listings.
- Extract job postings along with relevant skills and descriptions.
- Generate customized cold emails based on the extracted job information.
- Display the generated emails in an easy-to-read Markdown format.

## Libraries Used
- [Streamlit](https://streamlit.io/) - For building the web application interface.
- [LangChain](https://langchain.readthedocs.io/) - For handling natural language processing tasks.
- [Pandas](https://pandas.pydata.org/) - For data manipulation and analysis.
- [ChromaDB](https://www.trychroma.com/) - For managing and querying the portfolio data.
- [dotenv](https://pypi.org/project/python-dotenv/) - For managing environment variables.

## Execution Methodology
1. **Set Up Environment**: Ensure you have the required libraries installed. You can use the following command to install the dependencies:
  
    pip install streamlit langchain langchain-community pandas chromadb python-dotenv
   

2. **Environment Variables**: Create a `.env` file in the root directory and add your `GROQ_API_KEY`:
   
    GROQ_API_KEY=your_api_key_here


3. **Run the Application**: Launch the Streamlit app using the following command:
    
    streamlit run app.py
  

4. **Using the App**: 
   - Enter a URL containing job postings.
   - Click "Submit" to scrape job data and generate cold emails.
   - The generated emails will be displayed in a Markdown format for easy copying.



## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
