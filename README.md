## Introduction
In the world of machine learning and AI there are many different kinds of chat bots. Some chatbots are virtual assistants, others are just there to talk to, some are customer support agents and you've probably seen some of the ones used by businesses to answer questions. But we implemented a chatbot which gives answers to C++ questions.
## METHODOLOGY
The methodology that we used for this application is very simple. We used the concept of Natural Language Processing and building our own Neural network by using tflearn.
## Training Data
 We have used a json file “c++_assignment.json” for training our model. The intents.json is the file which consists of some sample chats and each chat block under a “tag”. This “c++_assignment.json” file is being created by our team and we have not used any file from the internet. 
We used this file for training the model and the model is being trained by using the method of tflearn and saved the model as “model.tflearn”. All the trained data is being stored in a file named “training_data” and further this file is used for giving responses
