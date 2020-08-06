# Jumpstart: Introduction to Machine Learning

## Setup
This setup guide was created to give participants more practice using console commands to retrieve data and setup python environments. This is not the only way to clone repos to new directories, or setup python environment, but offers an opportunity to try different method of setting up your workspace.

### Step 1: Cloning the git repository

On a Windows computer, open the Anaconda Prompt by pressing the Windows key, and typing `Anaconda Prompt`. 

On a Mac, open the Terminal application by pressing `Cmd + Space` and typing `terminal`. 

Clone the repository by typing, or copying, the following in Anaconda Prompt or Terminal: `git clone https://github.com/vrtompki/Jumpstart-ML-Workshop.git`.

Change into the new directory by typing `cd Jumpstart-ML-Workshop`.

### Step 2: Create a new environment

Create a new virtual environment for this project using `conda` and the provided `.yml` file. 

Type `conda env create -f jumpstart_ml_env.yml`. 

Activate the new environment: `conda activate jumpstart_ml`.

### Step 3: Open the workshop materials in JupyterLab

Start JupyterLab by typing `jupyter lab`. 

When JupyterLab opens in your browser, navigate to the folder where you cloned the repository, `Jumpstart-ML-Workshop`. Click on the file named `jumpstart-intro-ml.ipynb`. 

Now you're ready to start!

