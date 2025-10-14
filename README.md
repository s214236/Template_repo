# Template_repo
This Repo is meant as template for new repos

# How to get
1. Clone to GitHub desktop
2. Open in vscode and run the following in powershell "conda env create -f environment.yaml"
3. Run test.py to check if the environment works, make sure the script is run from the newly created environment

# Updating environment
1. Run "conda env update --file environment.yaml --prune" in powershell to get/delete packages not in the environment.yaml file
2. Run "pip install -e ." to make sure all local folder are considered as packages

# Adding/deleting packages
Edit the environment.yaml file
