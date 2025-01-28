<<<<<<< HEAD
# Chatbot Deployment with Flask and JavaScript

In this tutorial we deploy the chatbot that is created with Flask and JavaScript.

This gives  deployment option:
- Serve only the Flask prediction API. The used html and javascript files can be included in any Frontend application (with only a slight modification) and can run completely separate from the Flask App then.

## Initial Setup:
This repo currently contains the starter files.

Clone repo and create a virtual environment
```
$ git clone https://github.com/python-engineer/chatbot-deployment.git
$ cd chatbot-deployment
$ python3 -m venv venv
$ . venv/bin/activate
$ .\venv\Scripts\Activate
```
Install dependencies
```
$ (venv) pip install Flask torch torchvision nltk
```
Install nltk package
```
$ (venv) python
>>> import nltk
>>> nltk.download('punkt')
```
Modify `intents.json` with different intents and responses for your Chatbot

Run
```
$ (venv) python train.py
```
This will dump data.pth file. And then run
the following command to test it in the console.
```
$ (venv) python chat.py
```

Now for deployment follow my tutorial to implement `app.py` and `app.js`.


## About Chatbot



The chatbot gives info about our college NNRG , its placements , packages , clubs ,events ,faculty and thier url links , and also information related to  IT department 



static : app.js - for opening the chatbot window and closing the window 
images - contains chatot icon image 



templates :
base.html : it is used to develop the chatbot interface


model.py : NLP model is defined here 
=======
>>>>>>> edccc7d466c66d1168d9a50c172d1fcef9b1d213
