
## Building an End-to-End LLM Project with RAG and AI Agents

#### Custom Document QA
The FAISS vectorstore is used to retrieve documents relevant to a user’s query. The query and context are passed to the LLM to generate a meaningful response.

#### Real-time Web Search
**Tavily** lets you add real-time web search capability to your AI agents.


### CrewAI Agents

Task 3: Create a New AI Agent
- Define a new role (e.g., “Trend Analyst”).
- Give it the **Tavily tool** and a goal like “Summarize the latest news on AI”.

Task 4: Report Generator Agent
- Design an agent to collect insights and export them as a structured report (Markdown, PDF, etc.).

- Agents **collaborate** to achieve a shared objective (e.g., generate a report or perform research).


### End-to-End Framework
Create an API using flask/django or frontend using streamlit.

### Containerisation
Dockerise the flask API/streamlit app for deployment.
