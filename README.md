# MachineLearning
## Setup environment
* Install python and pip: https://github.com/BurntSushi/nfldb/wiki/Python-&-pip-Windows-installation
* Added to environment variable path: C:\Users\[username]\AppData\Roaming\Python\Python37\Scripts
* Update pip: pip3 install --upgrade pip
* Create an isolated environment: 
  ** Install virtualenv: pip3 install --user --upgrade virtualenv
  ** Create isoloated Python environment: cd to directory -> virtualenv env
* Activate this environment: env\Scripts\activate
* To Deactivate env: deactivate 
* In environment, install jupyter: pip3 install --upgrade jupyter matplotlib numpy pandas scipy scikit-learn
* Import modules: python -c "import jupyter, matplotlib, numpy, pandas, scipy, sklearn
* Start Jupyter: jupyter notebook