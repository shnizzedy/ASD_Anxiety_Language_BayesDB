# Setup
1. Download and install [Anaconda](https://www.anaconda.com/downloads)
2. BayesDB currently requires Python 2.7 which will soon be deprecated. To isolate the old Python that BayesDB relies on, we can create an Anaconda environment. In a directory where you want to work, create an Anaconda environment (I named mine `NickBayesDB`) by issuing the following commands in a terminal:
```sh
conda create -n NickBayesDB python=2.7 ipykernel
```
3. Activate the environment with this line (still in your terminal, replacing `NickBayesDB` with your environment's name):
```sh
source activate NickBayesDB
```
4. Install bayeslite in your environment (still in the terminal) with this line:
```sh
conda install -c probcomp bayeslite
```
5. Install the Python2 Jupyter kernel:
```sh
python -m ipykernel install --user
```
6. Let Jupyter know about the kernel:
```sh
pip install --upgrade jupyter
```

# Environment
To get in and out of your Anaconda environment that you created,
```sh
source activate NickBayesDB
```
and
```sh
source deactivate
```
replacing `NickBayesDB` with your environment's name

# Run
1. In a terminal, make sure you're in your Anaconda environment and in the directory your notebook is in. If you're in a non-default environment, your terminal will show that environment's name in parentheses before your login, and your current directory will show after a colon after your login, eg:
```sh
(NickBayesDB) shnizzedy: ~/ASD_Anxiety_Language_BayesDB$
```
If you need to activate your environment, see [Environment](#environment) above.
If you need to change directories, `cd` to the directory you need.
2. In your terminal, type
```sh
jupyter notebook
```
to launch the Jupyter notebook environment in your browser.
3. Click the `ASD_Anxiety_Language_BayesDB.ipynb` notebook to launch that notebook.
4. When you're done,
  1. Close your Jupyter browser tabs.
  2. Press `[Ctrl]+c` in your terminal to shutdown your Jupyter server
  3. In your terminal, type
```sh
source deactivate
```
to exit your Anaconda environment.
