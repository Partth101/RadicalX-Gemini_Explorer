# RadicalX-Gemini_Explorer

Description:
This Streamlit application allows you to interact with Google's Gemini language model (LLM), named ReX, in a chat-like interface. ReX can answer your questions, generate different creative text formats, and engage in informative conversations.

Features:

 • Chat interface for conversation with ReX
 • User name personalization
 • Persistent chat history across sessions
 • Emoji support (for potentially more interactive experiences)
  
Requirements:
 • Python 3.x
 • vertexai package (refer to installation instructions below)
 • streamlit package (refer to installation instructions below)

Installation:
 • Install required packages:
 • Bash
 • pip install vertexai streamlit
 • Use code with caution.
 • Set up Vertex AI project:
 • Create a Vertex AI project on Google Cloud Platform (GCP).
 • Install the Vertex AI SDK following the official guide: https://cloud.google.com/python/docs/reference/aiplatform/latest
 • Set the project variable in the code at the top to your Vertex AI project ID.

Usage:
 • Run the application:
 • Bash
 • streamlit run app.py
 • Use code with caution.
 • Enter your name: Type your name in the text input field and press Enter.
 • Start chatting: Ask ReX questions or provide prompts in the chat input field. ReX will respond with its output, personalized with your name.

Additional Notes:

This application uses the vertexai package, which provides a preview interface to interact with Vertex AI features.
The code includes a temperature and top_p parameter for the GenerationConfig class to control the randomness and focus of the generated text. These parameters can be further fine-tuned for different use cases.
Feel free to experiment with different prompts and questions to explore ReX's capabilities.
