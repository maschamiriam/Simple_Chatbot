This is a (simple) chatbot called 'Chatty' built with a decision tree model, which gets trained on sentence patterns of different categories (tags: greetings, joke, help etc.). After training, it processes a user input by predicting its category and provides a random answer of the same category. Since words are not an easy input to train and test a classification model, the sentences of the training data and the user input are converted into bag-of-words (bow) beforehand

Note: The dataset used for training is quite limited with 210 samples, 30 sentences of 7 categories (tags: greeting, goodbye, joke, help, thanks, name, purpose). Thus, the resulting model cannot provide elaborate or newly generated answers like we are used to from hugely trained LLMs, but will always choose a response from one of the provided categories. It cannot learn new words or themes as it bases its predictions solely on the words in the dataset patterns - the joke responses are still pretty funny.

Credits: Training dataset "ChatbotTraining.csv" from https://github.com/cornelius31415/ARTIFICIAL-INTELLIGENCE/tree/main/CHATBOT

Additionally, a GUI was added with tkinter to make the conversation with 'Chatty' more convenient. So let's chat! :)

Steps for building the chatbot application - details are found in the jupyter notebook:
1. Generating of Vocabulary and Bag of Words for Patterns in Dataset
2. Machine learning - Apply Decision Tree Classification on Chatbot Data
3. Building an Interaction between User & Chatbot
4. Creating a Graphical User Interface (GUI) for Chatbot
