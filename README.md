# Become_QA_auto
QA automation using Python.
This project includes framework to run automatic tets. 
It has a base structure: configuration, modules, tests.
All tests are marked by their functionality (API, database, UI) and are stored in different subfolders. Marks and gathered in file "pytest.ini".  

Instructions:
To run tests use pytest -m {mark}: 
"change": Tests that modify name of a user
"check": Tests that check users name
"http": Tests that check HTTP Protocol 
"api": Testing GitHub`s API
"database": Testing Database functionality 
"ui": Testing User`s Interface



