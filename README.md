# Setting up virtualenv
- Create a virtual env: `mkvirtualenv NAME_OF_PROJECT`
- Ensure that you're one the right env: `workon NAME_OF_PROJECT`
(it should now appear on your command line prompt)
- Install django: `pip install django`
- Verify: `pip list`
- Save new packages: `pip freeze > PROJECT_DIRECTORY/requirements.txt`


## Testing
- Coverage and testing pips to save to requirements.txt
`pip install coverage`
`pip install nose`
`nosetests --with-coverage test.py`


# Debugging with PDB
`import pdb; pdb.set_trace()`
