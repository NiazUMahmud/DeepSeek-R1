# DeepSeek R1: Your local AI Coding Companion

https://github.com/user-attachments/assets/cdf4d7cd-5cac-4db4-bc77-61d087c68297

This project implements a simple Streamlit application that leverages the power of the Ollama LLM (specifically the `deepseek-r1` models) to assist with various conversational task including coding. 

**Key Features:**

* **Code Generation:** Generate Python code snippets, functions, or even entire classes.
* **Debugging Assistance:** Get help identifying and fixing bugs in your code.
* **Code Documentation:** Generate concise and informative documentation for your code.
* **Solution Design:** Brainstorm and explore different solutions to coding challenges.

**Technologies Used:**

* **Streamlit:** For building the user interface.
* **LangChain:** For orchestrating the interaction with the LLM.
* **Ollama:** For providing the underlying language model.

**How to Run:**

1. **Install dependencies:**
langchain_core
langchain_community
langchain_ollama

2. **Start the Ollama server:** Ensure that the Ollama server is running locally on http://localhost:11434.
3. **Run the Streamlit app:**
streamlit run app.py

5. **Interact with the application:**
-Select the desired deepseek-r1 model in the sidebar.
-Type your coding questions or requests in the chat input box.
-The application will generate responses from the LLM and display them in the chat history.
**Customization:** 
**Model Selection:** Choose between different deepseek-r1 models (e.g., deepseek-r1:1.5b, deepseek-r1:3b) to adjust the model's capabilities.
**Prompt Engineering:** Experiment with different prompt styles and formats to improve the quality of the generated responses.
**Customization:** Modify the system_prompt and other parameters to tailor the AI assistant's behavior to your specific needs.
**Disclaimer:**
This is a basic example, and the performance of the AI assistant will depend on the quality of the prompts and the capabilities of the chosen LLM model.
