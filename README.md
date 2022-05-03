# A Framework for Extracting and Encoding Features from Object-Centric Event Data

###
Please first use anaconda prompt to create the environment.

``conda env create --file environment.yml``

then unzip the event log in example_logs/mdl/ and put it in the same directory.

Activate the environment in anaconda prompt

``conda activate icsoc``

Go into the repository directory and run 

``python experiments.py``

This will run all the experiments and reproduce the figures. Slight deviations might be due to differently initialized weights in the neural networks.
