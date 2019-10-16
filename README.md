# dash

To install all the necessary packages, do the following: 

### Step 1: 

**Option 1 (using Conda)**: 

Run the following command from your command line: 

`conda env create -f dash.yml`

**Option 2 (using Venv)**: 

Run the following command from your command line: 

`pip install -r requirements.txt`


### Step 2: 

To make the environment available in Jupyter notebook, run the following: 

`source activate myenv`

`python -m ipykernel install --user --name myenv --display-name "Python (myenv)"`
