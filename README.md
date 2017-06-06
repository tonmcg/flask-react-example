flask_react_example
=====================

A minimal example of an interactive scikit-learn model, using react and d3js.  

To run in a virtual environment without Anaconda installed:

```
	$ virtualenv venv
	New python executable in venv/bin/python
	Installing setuptools, pip, wheel...done.
	$ source venv/bin/activate
	(venv)$ pip install -r requirements.txt 
	...
	(venv)$ python react_example.py 
	 * Running on http://127.0.0.1:5001/ (Press CTRL+C to quit)
```

To run in a virtual environment with Anaconda installed:
 
```
	$ conda create -n venv python=2.7
	...
	proceed ([y]/n)? 
	$ y
	$ source activate venv
	...
	(venv)$ pip install -r requirements.txt
	...
	(venv) python react_example.py

```
then go to [localhost:5001](http://localhost:5001/).  