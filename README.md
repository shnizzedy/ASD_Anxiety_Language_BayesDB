# Setup
1. Download and install [Docker](https://docs.docker.com/install/#supported-platforms)
2. [Test](https://docs.docker.com/get-started/#test-docker-version) your Docker installation.
3. Get the probcomp notebook Docker image by running the following command in a terminal:
```sh
docker pull probcomp/notebook
```

# Environment
1. Start by running the following command in a terminal:
```sh
docker-compose up
```
2. When you're done,
    1. Close your Jupyter browser tabs.
    2. Press `[Ctrl]+c` in the same terminal to kill the Jupyter server.
    3. Close out by running the following command in a terminal:
```sh
docker-compose down
```

# Run
1. After running `docker-compose up`, open the link provided in your terminal.
2. Navigate to the `notebooks` directory in the Jupyter browser tab.
3. Click the `ASD_Anxiety_Language_BayesDB.ipynb` notebook to launch that notebook.
