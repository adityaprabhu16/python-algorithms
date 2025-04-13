## Commands:
Command + K to clear terminal
python --version
python3 --version

pip install notebook 

python -m venv venv
source venv/bin/activate

pip install notebook

jupyter notebook #activates the Jupyter notebook server locally so you can render notebooks.

Python environment (kernel) location (local):
#This will be in your local directory where you created this file.
venv/bin/python

If you get an error about RPC communication failed:
 - Increase the buffer size. 
 - git config --global http.postBuffer 157286400