# LLM_PROJECT
Equity_Research_Analysis

News Research Tool- WE can give bunch of news article url links to this tool and it will retrive the answer based on those news articles. Also, can select chunks for relevent link from where ans will be available.

Architecture:

(Documents{text loader}--Splite{Character Text Splitter}--Vector DB{FAISS - Facebook AI Similarity Search}--Retrieval{RetrievalQAWithSourceChain}--Prompt{LLM-Answer})

Work Flow:

1) Articles---Web scrapeper---OpenAI Embeddings will convert the text into---data vectorbase using AI or Lama or bird etc--- using Milverse Chroma, pine code to make database injection system
2) Chat Bot---question gets convert into open embeddings---vectordata base---pull relevent chunk (which matches with the question)---ULM

Technologies Used- LangChain, OpenAI, Streamlit
