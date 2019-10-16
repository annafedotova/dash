# dash

To install all the necessary packages, do the following: 

### Step 1: 

Run the following command from your command line: 

`conda env create -f dash.yml`


### Step 2: 

To make the environment available in Jupyter notebook, run the following: 

`source activate myenv`

`python -m ipykernel install --user --name myenv --display-name "Python (myenv)"`
