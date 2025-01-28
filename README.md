# Kakadoo Engine

<p align="center">
  <img src="https://github.com/user-attachments/assets/f431a57c-1fd8-4d11-b8bd-fb82bbd61b79" alt="Kakadoo Logo" width="400"/>
</p>

## Project Overview
Kakadoo Engine is an advanced cloud-based search engine designed to index and retrieve AWS-related content efficiently. The system supports a variety of features, including fun facts about AWS, an AI-powered chatbot for AWS queries, and detailed statistical insights about indexed data. This project demonstrates the power of microservice architecture and focuses on scalability, performance, and user experience.

## Technology Stack
- **Frontend**: Jupyter Notebook with interactive `ipywidgets`
- **Backend**:
  - Python
  - Firebase (Database)
  - BeautifulSoup (Web scraping)
  - NLTK (Natural Language Processing)
- **Visualization**: Matplotlib
- **Microservices**:
  - **Crawler Microservice**: Extracts and processes AWS domain pages.
  - **Index Creator Microservice**: Builds an efficient searchable index.
  - **Data Fetcher Microservice**: Retrieves data from Firebase.
  - **Query Microservice**: Processes user queries and ranks search results.
  - **Statistics Microservice**: Generates statistical insights.


### Usage
Navigate to the project folder.

Run the Jupyter Notebook: Open Kakadoo.ipynb in Jupyter Notebook and follow the cell execution sequence.

Start the Engine:

Execute the cells to initialize microservices and set up the environment.

## Core Features
**Multi-Module System:**

**Microservices** for crawling, indexing, querying, and administration.
Efficient role-based architecture for scalability.
**Search Engine:**

Processes queries in natural language.
Displays ranked results with URLs and titles.
**Fun Facts:**

Displays random AWS-related facts for user engagement.
**AWS Chatbot:**

Interactive Q&A interface powered by generative AI.
**Statistics Dashboard:**

Visual insights, including:
Most/least common terms.
Document frequency distribution.
Interactive graphs and charts.
**Admin Tools:**

Manage the index: delete, recreate, or fetch terms and documents.
Control term-specific URLs.
### Screenshots
Here are some screenshots of the application:

1. **Main Dashboard**
![image](https://github.com/user-attachments/assets/9a087328-863b-4ef4-88cc-712427090216)

2. **Search Results**
![image](https://github.com/user-attachments/assets/9be50de5-45dd-4568-a326-071f8bed61cf)

3. **Statistics Dashboard**
Most Common Documents
![image](https://github.com/user-attachments/assets/94aa5e57-9ac2-43c5-8730-6ceda1298c94)
Most Common Words
![image](https://github.com/user-attachments/assets/39042a0e-543a-481e-a385-8ba7d7cf77f7)

4. **AWS Chatbot**
![image](https://github.com/user-attachments/assets/b5235a48-e60b-4b22-9c59-93c7fb7175db)

5. **Admin Index Management**
![image](https://github.com/user-attachments/assets/fdc2eb1c-74c3-4a18-96b1-cef2d6d8605c)

## Project Outcomes
Built an efficient AWS search engine with query processing and ranked results.
Successfully integrated microservices for modular development.
Optimized user experience with a responsive and interactive GUI.
