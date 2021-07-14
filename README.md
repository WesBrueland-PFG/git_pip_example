# git_pip_example


Example repo of how to structure your python project to pip installable from a github repo.

This project uses a github action to build and commit the build files directly back to the package source when a change is pushed to the main branch. 


Based on this article:

https://packaging.python.org/tutorials/packaging-projects/
  
To install, use:
```
pip install git+https://github.com/WesBrueland-PFG/git_pip_example.git
```
After installation, to use with python:
```
>>> from hello_remote import hello_remote
>>> hello_remote.hello()
Hello remote world!
```
