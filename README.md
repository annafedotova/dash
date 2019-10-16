# dash

To install all the necessary packages, do the following: 

### Option 1: 

Run the following command from your command line: 

`conda env create -f dash.yml`


### Option 2: 

Run the following command from your command line: 

`conda create --name <env> --file requirements.txt`


To make the environment available in Jupyter notebook, run the following: 

`source activate myenv`

`python -m ipykernel install --user --name myenv --display-name "Python (myenv)"`
