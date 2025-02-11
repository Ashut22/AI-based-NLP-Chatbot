# AI-Based NLP Chatbot with GUI  

## Project Overview  
This project is an **AI-driven chatbot** built using **deep learning and natural language processing (NLP)**. The chatbot is designed to predict user intents and provide relevant responses through a **Tkinter-based graphical user interface (GUI)**. It includes features like **chat saving, web search, and real-time time retrieval**.  

## Objective  
To build an advanced AI chatbot using deep learning and NLP techniques that can efficiently understand and process diverse user queries, providing accurate and relevant responses through an interactive and user-friendly GUI.  

## Approach  
1. **Data Preprocessing and Model Training**  
   - Tokenized and lemmatized user queries.  
   - Built a bag-of-words model and trained a neural network using TensorFlow for intent classification.  
   
2. **GUI Development**  
   - Developed a chatbot GUI using Tkinter for seamless user interaction.  
   - Integrated features like chat saving, web search, and real-time time display.  

3. **Intent Prediction and Response Generation**  
   - Implemented intent prediction using the trained model.  
   - Generated context-based responses using predefined intents and random response selection.  

## Features  
- **Intuitive and Interactive GUI:** Provides a user-friendly interface for smooth interactions.  
- **Real-time Time Retrieval:** Responds with the current time upon user request.  
- **Web Search Integration:** Opens a browser search when requested.  
- **Chat Saving:** Saves the conversation history in a text file.  
- **Exit Command:** Supports commands like "exit," "quit," or "bye" to end the conversation.  

## Technologies Used  
- **Python**  
- **TensorFlow (for model training)**  
- **NLTK (for NLP tasks)**  
- **Tkinter (for GUI development)**  

## How to Run the Project  
1. Clone the repository or download the project files.  
2. Ensure you have the required libraries installed:  
3. Download NLTK data if not already installed:  
```python
import nltk
nltk.download('punkt')
nltk.download('wordnet')
project_root  
  ├── main.py             # Model training and data preprocessing  
  ├── gui.py              # Chatbot GUI and response handling  
  ├── Intent.json         # Predefined intents and responses  
  ├── Chatbot_model.h5    # Trained model file  
  ├── words.pkl           # Serialized words for bag-of-words  
  ├── classes.pkl         # Serialized intent classes  
  └── README.md           # Project documentation  

