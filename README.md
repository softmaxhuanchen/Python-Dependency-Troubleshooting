# Python-Dependency-Troubleshooting
1. Check Installed Packages
   pip list
   conda list
2. Virtual Environments
   conda create --name myenv python=3.8
   conda activate myenv
3. Installing Packages
   pip install libraryname==1.2.3
   conda install libraryname=1.2.3
4. Update Packages
   pip install libraryname --upgrade
   conda update libraryname
5. Check for Dependency Conflict
   pip install pipdeptree
   pipdeptree --warn
6. Uninstalling & Reinstalling
   pip uninstall libraryname
   conda remove libraryname
7. Clean Cache
   pip cache purge  

    
