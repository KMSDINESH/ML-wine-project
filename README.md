# ML-wine-project


### Workflows
#### 1. Update config.yaml
#### 2. Update schema.yaml
#### 3. Update params.yaml
#### 4. Update the entity
#### 5. Update the configuration manager in src config
#### 6. Update the components
#### 7. Update the pipeline
#### 8. Update the main.py
#### 9. Update the app.py


### 01. Create a conda environment in git bash
'''
conda create -n mlproj python=3.8 -y
'''
#### If conda is not working in the git bash. Open anaconda prompt and run the following command.

conda init bash

#### Note: If you don't have anaconda in your sytem, please install.

### 02. Activate the environment
'''
conda activate mlproj
'''

### 03. Create the folder structure
#### please check the template.py file. It is the code to create the required files and folders all at once, instead of creating one by one during process. And save the file. and run the following command.
'''
python template.py
'''

### 04. install the requirements
'''
pip install -r requirements.txt
'''

