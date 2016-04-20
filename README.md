# python-demos 

## python version 
Python 2.7.11 

Use virtualenv 
 
# 1. install virtualenv 
pip install virtualenv 
 
# 2. go into the root directory of python-demos 
 
# 3. set up the virtual environment 
virtualenv -p <PYTHON_HOME/python.exe> venv # Windows 
 
# 4. activate the virtual env 
$ source venv/bin/active # MAC OS X 
 
$ venv\Scripts\activate # Windows 
 
# 5. install scrapy 
$ pip install scrapy 
 
# 6. exceptions.ImportError: No module named win32api 
first downloads the pywin32 

refers to https://sourceforge.net/projects/pywin32/files/pywin32/Build%20220/pywin32-220.win-amd64-py2.7.exe/download 
 
$ easy_install C:\Users\[Your Username]\Downloads\pywin32-220.win-amd64-py2.7.exe 
 
# 7. test 
$ scrapy runspider scrapy_demo/myspider.py 
 
 or 
 
$ cd scrapy_tutorial 
$ scrapy crawl dmoz 
 
# 8. exit the vritual envs 
deactivate