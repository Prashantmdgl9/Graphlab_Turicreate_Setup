There can be certain issues while installing turicreate or graphlab
Graphlab is paid version while the opensource is called turicreate.

It works on python 3.7, they say that it works for 3.8 but it throws error. 
The above statement is valid on Aug 29 2020


# Steps to follow:
1. Install python 3.7.9
2. Install virtualenv, pip3 install virtualenv
3. virtualenv env_1
4. activate the virtual env by source env_1/bin/activate
5. pip install -U turicreate

Turicreate should be installed now


Other libraries to install:
1. sudo pip install -U jupyter
2. pip install ipykernel
3. python -m ipykernel install --user --name=env_1
check the kernel.json and virtual env should be associated with python


