## Description
This projects is inspired byt SalesGPT and other open source projects. But not copy paste, or any idea has not been stolen. Thanks to all the contributors.
Here, it is a streamlit interface with two options: Walmart Bot and SearchGPT.
Walmart_Bot: You can use this interface to search for products on Walmart and also get answers of any product related questions(like: What is the price of iPhone 12?, Compare feature of products). You will get source/product link along with the answer.
I have used OpenAI models, you can use any open sources model from HuggingFace as well. Langchain has been used to make system, I have used Prompt engineering, RetrievalQA, tools, Vector Database, and other techniques to make this system. Pincecone has been used as vector database. You can use any other vector database/traditional database as well using llamaindex. OpenAI embedding has been used, but open-source embeddings can be performed.
FastAPI has been used to make the API, but you can use Flask or any other framework as well.
Streamlit has been used to make the interface, but you can use any other framework as well.
SearchGPT: You can also use this interface to search for any question and get answers from the internet.
LangChain and different tools have been used along with large language model to make this system.

## Folder Structure
- .env
- .gitignore
- csv_to_vectore_database(pinecone).ipynb
- Data
  - WMT_Grocery_Data.csv
- Images
  - bg-image.png
  - searchGPT_screenshot.png
  - walmart_bot_screenshot.png
- Dockerfile
- README.md
- requirements.txt
- streamlit_interface.py
- walmart_functions.py
- search_capabilites.py
- run_api.py

## How to run the project
Using Docker:
```
docker build -t bot .
docker run -p 5000:5000 bot
```
Using Streamlit:
```
streamlit run streamlit_interface.py
```

## How to use the project
You can use this interface to search for products on Walmart and also get answers of any product related questions(like: What is the price of iPhone 12?, Compare feature of products). You will get source/product link along with the answer.
You can also use this interface to search for any question and get answers from the internet.

## How to contribute
You can contribute by adding more features to the system, or by adding open source models/embeddibg to the system. You can also contribute by changing interface to the system. You can also contribute by adding more features to the interface.

## How to deploy the project
You can deploy the project using Docker or Streamlit. You can also deploy the project using Heroku, AWS, or any other cloud platform.

## How to contact the author
You can contact me at: [LinkedIn](https://www.linkedin.com/in/shaon2221)
