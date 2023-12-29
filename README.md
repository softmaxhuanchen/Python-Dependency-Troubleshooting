# Python-Dependency-Troubleshooting
## 1. Check Installed Packages
   ### pip list
   ### conda list
## 2. Virtual Environments
   ### conda create --name myenv python=3.8
   ### conda activate myenv
   ### conda env list
   ### conda env remove --name myenv
   ### conda create --name newenv --clone myenv
   ### Using YAML files
   ### a. Export the current environment to a YAML file:
   ### conda activate dev
   ### conda env export > dev.yml
   ### b. Create a new environment from the YAML file:
   ### conda env create --name dev --file dev.yml

## 3. Installing Packages
   ### pip install libraryname==1.2.3
   ### conda install libraryname=1.2.3
## 4. Update Packages
   ### pip install libraryname --upgrade
   ### conda update libraryname
## 5. Check for Dependency Conflict
   ### pip install pipdeptree
   ### pipdeptree --warn
## 6. Uninstalling & Reinstalling
   ### pip uninstall libraryname
   ### conda remove libraryname
## 7. Clean Cache
   ### pip cache purge  

## 8. recreate a conda env for fintech
   ### conda deactivate
   ### conda update conda
   ### conda create -n dev python=3.10 anaconda
   ### conda activate dev

    
