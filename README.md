# Basic NLP with nltk package in Python

## Install requirements

- Create a virtual enviroment with python 3.5
  
  ```
  virtuanv --distribute -p /python/3.5/path nltk_base
  ```
  
  or in OSX:
  
  ```
  pyvenv-3.5 nltk_ex
  ```

- Clone the repo
	
  ```
  git clone https://github.com/brunifrancesco/nltk_base.git
  ```

- Move to cloned folder
  
  ```
  cd nltk_base
  ```

- Activate the virtualenv
  
  ```
  source ../bin/activate
  ```

- Install requirements
  
  ```
  	pip install -r requirements.txt
  ```

- Download nltk data (run a python shell):
  
  ```
  import nltk
  nltk.download()
  ```

## Run the notebook
- Activate the virtual env (just cd into the virtualenv dir)

  ```
  source bin/activate
  ```

- Run the notebook
  
  ```
  ipython notebook
  ```
- Hack it :)
