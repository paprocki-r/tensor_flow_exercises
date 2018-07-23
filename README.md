#TODO
https://developers.google.com/machine-learning/crash-course/

# tensor_flow_exercises
practical examples with Tensor Flow - step by step

I. Create virtual environment
  1. Go to terminal and type 
  
    python3 -m venv .venv
  
  This will create virtual environment for this project. 
  
  2. Activate virtual environment - type in terminal 
    
    source .venv/bin/activate
  
  With it you can install and remove packages and it will not interfere with your system instantion of python.
    
  3. Install required packages
  a) create text file requirements.txt and paste
  
    tensorflow==1.4.1
    scipy==1.0.0
    scikit-learn==0.19.1
    matplotlib==2.1.1
    xlrd==1.1.0
    ipdb==0.10.3
    Pillow==5.0.0
    lxml==4.1.1

  b) in terminal type
  
    pip install -r requirements.txt

  It will download and install all packages required in requirements.txt file
    
II. Running scripts
  1. Running python scripts - in terminal type:
    
    python name.py 
    
  or for interactive mode
  
    python -i name.py
  
III. Tensorboard
  1. In terminal type:
  
    tensorboard --logdir="./graphs" --port 6006
  
  2. Go to your webbrowser and type the address:
  
    localhost:6006
 
IV. EXAMPLES
  1. Linear Regression
  a) Find a linear relationship between X and Y to predict Y from X.  Model the linear relationship between:
  dependent variable Y
  explanatory variables X

  b) Dataset: X: birth rate
  Y: life expectancy
  190 countries



