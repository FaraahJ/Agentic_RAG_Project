# PROJECT 3: Retrieval Augemented Generation Project
This repository aims to explore the coding and features behind a Retrieval Augmented Generation (RAG) application using Groq, OpenAI and Tavily.

📂The [crew_data](https://github.com/FaraahJ/Agentic_RAG_Project/tree/main/crew_data)  directory contains all PDF documents used in this project and were chosen at random from [this Kaggle dataset](https://www.kaggle.com/datasets/manisha717/dataset-of-pdf-files ).

In the main repository you will find:

- 📓[FAISSBuild.ipynb](https://github.com/FaraahJ/Agentic_RAG_Project/blob/main/FAISS_Build.ipynb), in which a Large Language Model, an embedding model and the main RAG PDF-based tool were established using OpenAI’s Groq, Huggingface and Langchain packages. A FAISS vectorstore was created to convert text into vectors and perform a similarity search. Visualisation of this search was attempted using the t-SNE method. New document data was then added to the existing FAISS Index and retrieval was tested with a new query input.

- 📓[Tavily Agents.ipynb](https://github.com/FaraahJ/Agentic_RAG_Project/blob/main/Tavily_Agents.ipynb ), in which a real-time web search retrieval system was built using CrewAI and Tavily tools. Seven different Tavily agents, their roles and their tasks were defined before assembling them together to answer an input query. 
