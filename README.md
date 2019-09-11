#      Hands-On NLP        #

## Getting started
First, we need to get set up with the virtual environment that contains all of the required libraries to run the code.  Make sure you're running Python 3 which comes preinstalled with venv (virtualenv in Python 2)

Start by creating a new virtual environment

```
python3 -m venv miami
```

or

```
/usr/local/bin/python3.7 -m venv miami
```
if `python3` is not set to your base installation of python3.7.

Then activate the virtual environment:

```
source miami/bin/activate
```

Now we're ready to install the dependencies.  From the top level directory run:

```
pip install -r requirements.txt
```

Finally, with the `miami` environment activated, run the Jupyter Notebook to get started with the code

```
jupyter notebook hands_on_nlp.ipynb
```


