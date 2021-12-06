Create enviroment and activate enviroment

~$ conda env create -f requirements.yml
~$ conda activate personal_env

Put env as a visible kernel in jupyter

~$ pip install ipykernel

~$ python -m ipykernel install --user --name=personal_env
