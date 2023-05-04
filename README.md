# cookiecutter-ipynb-project

## Cookiecutter Options
- **repo_name:** The name of the repository aka the toplevel folder.
- **project_name:** Name of the folder where the actual code is put in. This will also be the name by which the code can be imported globally in python.
- **author:** Name of the author of the package. Used in the MIT License file and the `setup.py` file.
- **email:** Email of the author. Used in the `setup.py` file.
- **remote_url:** Optional URL of an empty github repository. The repo created by the template is pushed to this repo. To avoid merge conflicts make sure to create an empty repo on github with no `.gitignore` file and no `README.md` file as these files as already created by the template.
- **environment:** The type of development environment to use. The environment is created fresh and the created repo gets automatically installed into it.

## Generated Project Structure
    {{cookiecutter.repo_name}}
    ├── {{cookiecutter.project_name}}
    │   └── __init__.py
    ├── notebooks
    │   └── 00_experiments.ipynb
    ├── .gitignore
    ├── setup.py
    ├── LICENSE
    └── README.md
