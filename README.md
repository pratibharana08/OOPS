# Clean code
I aim to learn to develop a code that can be reused and shared efficiently.This also helps in version control and avoiding code loss.Refactoring code in an integral part of coding to make it more usable.
The code is created in Jupyter notebook.Though I am using python 3.7, I will be explaining how we can create an environment with a different version and list.

##Creating an environment
The environment is just created to keep the required versions of libraries and packages installed, so no further version updation affects the code implemented. We can simply create the environment in  the Integrated Development Environment(IDE). Using Anaconda, we launch the shell and use the syntax: 
conda create -n or --name <name> <packages>.
 Example: conda create -n newEnvironment Python=2.7
  
To activate we can use *activate <name>* and then further use *deactivate <name>*  to deactivate.We can install packages when the environemnet is active.
  
## Listing in the jupyter notebook
We need to install ipykernel to list the environment in the notebook
conda install -c anaconda ipykernel
Post this we use the below command to access the commant in jupyter notebook
python -m ipykernel install --user --name=newEnvironment

## Object oriented programming
Unlike procedural programming, we build blocks of code around an object; here we will do it for a mobile store.
We will start by creating a class with objects in it. These obejcts have attributes and various changes can be implimented to it.


This is based on the AWS foundational course in ML on Udacity
