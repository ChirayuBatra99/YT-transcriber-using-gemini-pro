## Requirements and Virtual Environment:

1. To setup a virtual environment to install all the packages we can use the command: 
**python3 -m venv YOUR_ENVIRONMENT_NAME**
2. After creating the virtual environment, we can install the packages by following the below steps.
3. Requirements are mentioned in the requirements.txt file and can be installed using the command:  pip3 install -r requirements.txt
  (You can use pip3 if using python 3)

## Setup .env file
 Using the format provided in the .envExample file, we can setup our .env file for our secret keys.

## Run the project:
 We can run the project in the terminal using the command: python3 app.py
  And can make observations on how everything is working.

## Streamlit deployment:
1. The project has been deployed on Streamlit as well. Simply after cloning the project to local,and typing the command:       
**streamlit run app.py**

   
2. We can see the project opening on the localhost and give the inputs in the input fields(sample youtube video URL) and get the desired output (Summary of transcript of that video).


