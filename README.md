# Pipenv base cookiecutter template

[cookiecutter](https://cookiecutter.readthedocs.io) template for pipenv users. Provide some useful utility
 functions while somehow trying to stay technology agnostic (exceptions: pipenv for package manager, loegger for 
logging and pytest for testing).
  
Notes:
- Use pipenv to save dependencies and create virtual environment. 
- The setup_env.py script allow to set the environment variable of the pipenv. 
- Some helper functions help to read the configuration parameter, generate cache files and configure logging. 
- Pytest as test tool in dev
- Use configparser and config.ini to manage configuration parameters
- Path and other project properties can be added in config.ini
- Only for Python 3

## Installation
```
$ cookiecutter https://github.com/lyndametref/pipenv-base-cookiecutter
```

## Feedback
Feel free to give your feedback on github issue section. If you found a bug and know how to correct it, don't
 hesitate to create a  pull request.