# continuous-integration

### what to find on this repo
test CI with Travis and pytest.  
inpired by these 7 volumes: https://ilovesymposia.com/2014/10/01/continuous-integration-0-automated-tests-with-pytest/    

### introduction to pytest
https://www.youtube.com/watch?v=LdVJj65ikRY 

### requirements
sudo pip install pytest  
sudo pip install pytest-cov   
Travis CI and github accounts      

###usage 
git clone https://github.com/ksator/continuous-integration.git  
cd continuous-integration/  
py.test  
py.test --cov maths.py  
py.test --cov-report term-missing --cov=maths.py  







