# cashbook_blockchain
https://github.com/noahwalugembe/Cashbook.git
Developing a blockchain application from scratch in Python


### Instructions to run

Start a blockchain node server,

```sh
>>> python cashbook_server.py
```

Run our application,

```sh
>>> python run_app.py
```

The application should be up and running at [http://localhost:5000](http://localhost:5000).

Here are a few screenshots

1. Posting some content


2. Requesting the node to mine


3. Resyncing with the chain for updated data



To play around by spinning off multiple custom nodes, use the `add_nodes/` endpoint to register a new node.
To update the node with which the application syncs, change `CONNECTED_NODE_ADDRESS` field in the [views.py](https://github.com/noahwalugembe/Cashbook/master/app/views.py) file.
