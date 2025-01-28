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

### Core Features
## Multi-Module System:

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

Main Dashboard

Search Results

Statistics Dashboard

AWS Chatbot

## Project Outcomes
Built an efficient AWS search engine with query processing and ranked results.
Successfully integrated microservices for modular development.
Optimized user experience with a responsive and interactive GUI.
Conducted peer reviews and achieved an SUS score of 85.4, indicating high usability.
Acknowledgments
This project was developed by Team Kakadoo as part of a cloud computing course. Special thanks to the instructors and reviewers for their feedback and support.
