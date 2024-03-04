# RadicalX-Gemini_Explorer

Description:
This Streamlit application allows you to interact with Google's Gemini language model (LLM), named ReX, in a chat-like interface. ReX can answer your questions, generate different creative text formats, and engage in informative conversations.

Features:

 • Chat interface for conversation with ReX<br>
 • User name personalization<br>
 • Persistent chat history across sessions<br>
 • Emoji support (for potentially more interactive experiences)<br>
  
Requirements:
 • Python 3.x<br>
 • vertexai package (refer to installation instructions below)<br>
 • streamlit package (refer to installation instructions below)<br>

Installation:
 • Install required packages:<br>
 • Bash<br>
 • pip install vertexai streamlit<br>
 • Use code with caution.<br>
 • Set up Vertex AI project:<br>
 • Create a Vertex AI project on Google Cloud Platform (GCP).<br>
 • Install the Vertex AI SDK following the official guide: https://cloud.google.com/python/docs/reference/aiplatform/latest<br>
 • Set the project variable in the code at the top to your Vertex AI project ID.<br>

Usage:
 • Run the application:<br>
 • Bash<br>
 • streamlit run app.py<br>
 • Use code with caution.<br>
 • Enter your name: Type your name in the text input field and press Enter.<br>
 • Start chatting: Ask ReX questions or provide prompts in the chat input field. ReX will respond with its output, personalized with your name.<br>

Additional Notes:

This application uses the vertexai package, which provides a preview interface to interact with Vertex AI features.
The code includes a temperature and top_p parameter for the GenerationConfig class to control the randomness and focus of the generated text. These parameters can be further fine-tuned for different use cases.
Feel free to experiment with different prompts and questions to explore ReX's capabilities.
