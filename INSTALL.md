Create enviroment and activate enviroment

~$ conda env create -f requirements.yml
~$ conda activate omar_env

Then install all libraries:

~$ pip install path/to/folder/repository --user

For editing mode -e, use the following command:

~$ pip install -e path/to/folder/repository --user

Or within the repository folder:

~$ pip install -e .
