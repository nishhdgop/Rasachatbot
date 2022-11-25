# Rasachatbot
## Introduction
The chat bot built here is a contextual assistant built using Rasa. The contextual assistant mimics human conversations and takes into consideration what the user said before, when and how the user said it. Considering the context also means being able of understand and responding to different user inputs. Rasa's machine - learning based approach is used to learn from conversational data. 
Rasa is a set of open source machine learning tools used by developers for developing conversational AI. It has 2 main components 
 1. NLU: An open-source natural language processing tool for intent classification and entity extraction.
 2. Core: Framework for machine learning based contextual decision making.

### Set-Up
run the following commands
1. rasa init
- By running this command the initial files will be set up. Once the set up is complete required intents can be added to nlu.md file.  
2. rasa train nlu
- Once all the changes are done the model can be trained by running the above command. The trained model is saved into the models folder.
3. rasa shell
- This command opens up a chat bot that allows user to interact with the bot.

#### Sample Interaction:
<img src="./Screenshot 2022-11-25 at 7.12.21 PM.png" width="500" align="middle">

