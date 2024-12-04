# How to work with this Repository

Add an virtual environment for python if not already done
python -m venv clipboardListener-env

Activate the venv
On Windows, run:

clipboardListener\Scripts\activate On Unix or MacOS, run:

source clipboardListener/bin/activate

install needed packages
python -m pip install -r requirements.txt

Update the requirements.txt file for new added packages
python -m pip freeze > requirements.txt

###### Please note that some Notebooks could throw errors, especially test cases due to keras 3.0 in newer tensorflow versions


## At the end you will be able to implement the lunar landing simulation with reinforcement-learning
