# NLP Project (University)

###### Technologies Used: NLTK, TensorFlow, Keras, tkinter

This project is another academic endeavor undertaken by our team, aimed at developing a simple chatbot utilizing the Long Short-Term Memory (LSTM) model. The chatbot is designed to engage users by understanding their messages and providing appropriate responses. It is trained on a dataset that consists of various categories (intents), associated patterns, and corresponding responses. The LSTM model plays a crucial role in classifying the category to which a user's message belongs, subsequently generating a random response from a predefined list.



## Step 1: train_model.py

- **Data Preprocessing**:
    - Tokenization of input sentences.
    - Stemming of each word from the tokenized output.
    - Conversion of all text to lowercase.
    - Removal of punctuation.

- **Input and Output Datasets**:
    - Creation of a bag-of-words model.
    - The input comprises the patterns, while the output consists of the corresponding tag for each pattern.

- **Model Architecture**:
    - The neural network comprises three layers:
        - First layer: 128 neurons.
        - Second layer: 64 neurons.
        - Output layer: Number of neurons equal to the number of intents, utilizing a softmax activation function for output prediction.

- **Model Training**:
    - The model is trained for 200 epochs.

- **Serialization**:
    - Saving the trained model for future use.

## Step 2: user_interface.py

- The user interface is developed using the Tkinter library in Python, providing a graphical interface for user interaction.





Contextual Chatbots with Tensorflow https://chatbotsmagazine.com/contextual-chat-bots-with-tensorflow-4391749d0077

Python Chatbot Project – Learn to build your first chatbot using NLTK & Keras https://data-flair.training/blogs/python-chatbot-project/
