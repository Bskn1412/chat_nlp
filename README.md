<h1>Chatbot Using NLP and Logistic Regression</h1>
<p>Welcome to the Chatbot Using NLP and Logistic Regression repository! This project implements an interactive chatbot capable of understanding user intents and delivering meaningful responses. The system is built using Natural Language Processing (NLP) techniques and Logistic Regression, combined with an intuitive interface powered by Streamlit.</p>

<h3>Features</h3>
1. Intent Recognition: Uses TF-IDF vectorization and Logistic Regression to classify user queries into predefined intents.<br>
2. Interactive User Interface: A modern and accessible chatbot interface built with Streamlit.<br>
3. Conversation Logging: Saves user-chatbot interactions for future analysis and improvements.<br>
4. Customizable Intents: Easily update intents and responses by editing the intents.json file.<br>
<h3>Table of Contents</h3>
1. Getting Started<br>
2. Installation<br>
3. Usage<br>
4. How It Works<br>
5. Future Enhancements<br>
6. Contributing<br>
<h3>Getting Started<h3>
<h3>Installation</h3>
<h4>Prerequisites</h4>
* Python 3.8 or higher<br>
* Libraries: streamlit, nltk, scikit-learn, numpy<br>
<h4>Steps</h4> 
1. Install dependencies:
      pip install -r requirements.txt <br>
2. Download NLTK data (if not already installed):
      import nltk<br>
      nltk.download('punkt') <br>

<h3>Usage</h3>
1. Run the chatbot application:
     streamlit run app.py<br>
2. Open the provided URL in your browser.<br>
3. Interact with the chatbot by typing queries and viewing responses.<br>

<h3>How It Works</h3>
   <h4>Workflow</h4>
    1. User Input: The user types a query.<br>
    2. Preprocessing: Input is tokenized and vectorized using TF-IDF.<br>
    3. Intent Classification: Logistic Regression predicts the intent based on the processed query.<br>
    4. Response Generation: The chatbot retrieves a response associated with the predicted intent.<br>
    5. User Output: The response is displayed in the chatbot interface.<br>
  <h4>Data Source<h4>
    <p>All intents and responses are stored in a JSON file (intents.json), making it easy to customize or extend the chatbot's capabilities.</p>

<h3>Future Enhancements<h3>
  * Multilingual Support: Expand the chatbot to handle multiple languages.
  * Dynamic Learning: Incorporate a mechanism to improve responses based on user feedback.
  * Integration with Advanced Models: Implement BERT or GPT for more robust intent recognition.
  * Enhanced Deployment: Host the chatbot on platforms like WhatsApp, Slack, or as a PWA.
<h3>Contributing</h3>
<p>Contributions are welcome! If you have suggestions, feel free to fork this repository, create a branch, and submit a pull request.</p>

<h3>Acknowledgements</h3><br>
* Scikit-learn for machine learning algorithms. <br>
* Streamlit for creating the user interface. <br>
* NLTK for text processing and tokenization. <br>
<strong>Feel free to reach out with any questions or suggestions. Happy coding! 😊</strong>
