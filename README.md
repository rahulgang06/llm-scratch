training.py file contain the all the module which required for create the llm from scratch.
chatbot.py file having the pkl file which we get from the training.py. Model is trained from scratch using this dataset : https://huggingface.co/datasets/Skylion007/openwebtext 
Clone this repo -> run pip install -r requirements.txt -> download the dataset from above huggingface link.
Run the training.py for train the model use the pkl file generated from this and then run the chatbot.py file 
cmd to run chatbot.py : python chatbot.py -batch_size = 32. 
