
# Semantic_search_doc_Q-A_NLP
In order to modernise the search process, this project suggests fusing semantic search methods with GPT-3 question answering capabilities. High-quality responses to search queries can be created by utilising GPT-3's language creation capabilities.


## Screenshots

![image](https://user-images.githubusercontent.com/94490443/221265095-dc37bb92-2c1f-4517-9558-6388b1d1ca30.png)



## Code Modules functions(Code Flow) :
1.	To get the webpage's HTML content, use the requests library to scrape data from a website.
2.	To extract the plain text from the HTML content, use the BeautifulSoup library.
3.	Divide the plain text into smaller sections so that GPT-3 can process them more quickly.
4.	Use a language model, such OpenAI's GPT-3 model, to convert each block of text into a vector.
5.	In a database, keep the encoded vectors and information about each chunk's context and ID.
6.	Provide the information you are looking for in the text by creating a prompt or query.
7.	To find text passages that meet the prompt or query, use the GPT-3 model to search the index.
8.	Process the results returned by the model to extract the relevant information and present it to the user.

## Documentation

[OpenApi-Api key/Docs/introduction](https://platform.openai.com/docs/introduction)




## Installation

Install Semantic_search_q&a repo

Change the 'Api-key' from OpenAi and Pinecode  

## Install dependencies
   ```
   pip install Streamlit
   pip install sentence_transformers
   pip install requests
   pip install BeautifulSoup4
   pip install pinecode
   pip install openai 
```


## Run Streamlit on Browser
```bash
 Streamlit run app_name  
```

    
