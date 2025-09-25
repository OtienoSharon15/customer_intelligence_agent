# intelligent_customer_support_chatbot
This customer support chatbot project demonstrates a workflow-based customer support agent that categorizes clients' queries, detects negative sentiment, and routes questions to the appropriate handler. It is built with Python and deployed using Gradio for easy interaction.

# Technologies 
Technologies used include: PythonLangGraph, Langchain, Groq API (LLM model), Gradio (user interface), and dotenv (environment variable management).
While LangGraph handles the sequence of steps automatically, Langchain and Groq API provide the language model intelligence for classification and sentiment analysis. dotenv ensures API keys and environment variables are managed securely. The chatbot is deployed via Gradio, allowing users to interact with it in real time. It demonstrates a simple yet effective approach to AI-driven customer support.

# The workflow 
The chatbot works as follows: 
• The user submits a question through the Gradio interface
                    ↓
The chatbot classifies the query into Technical, Billing, or General categories
                    ↓
The bot evaluates and determines if the sentiment/emotion is Positive, Neutral, or Negative. If negative, the case is escalated to a human agent.
Technical, billing, and general questions are responded to accordingly, enhancing the overall customer experience.
