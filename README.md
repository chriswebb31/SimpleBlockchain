# SimpleBlockchain
A simple blockchain application where the blocks are messages on a forum

To download dependencies:

`pip install -r requirements.txt`

To run the server on MacOS:

`export FLASK_APP=node_server.py`

`flask run --port 8000`

After, on a different terminal window:

`python run_app.py`

Then go to:

`localhost:5000`

Type a message, along with your name and click **post**

Then **request to mine**

Then **resync**
