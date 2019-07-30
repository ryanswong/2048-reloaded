# 2048-reloaded
A revamped python 2048 game

## Getting Started
### 1. Install [git](https://git-scm.com/downloads)
We will be using git to version control the project as well as allow for group contribution.

**Helpful articles on how to use git:**

* [Getting Started on Git and Github (Lots of great links)](https://github.com/maptime/getting-started-with-git-and-github/blob/master/README.md)
* [Github Guide (10 minute read)](https://guides.github.com/activities/hello-world/)
* [Learn Git with Bitbucket Cloud](https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud)
* [Official git Documentation](https://git-scm.com/book/en/v1/Getting-Started-Git-Basics)
* [Git commands cheat-sheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet/)

**Cloning this project**

* Open your cmd/terminal/ (wherever you want to run your git commands), go to your directory (I would recommend making a "projects" folder) where you want the 2048-reloaded project folder to rest in. 

* Then type in:

        git clone https://github.com/suzuryu9000/2048-reloaded.git

* When you use dir/ls, you should see the "2048-reloaded" folder there


### 2. Make a virtual environment and use pip-tools (OPTION 1)

* Before you download the packages, I recommended you use virtual environments. You can use venv to create a virtual environment inside your 2048-reloaded project folder. (just make sure that you do not commit the python environment files to remote repository) 

  This has everything [Installing Virtual Env](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)

* Go to the project folder and create the python environment:

        python -m venv <ENVIRONMENT NAME>

* Then activate the virtual environment:

        env/Scripts/activate
        
* you should now see `(env) C:\User\PATH\.. ` on the left side after this
* Install pip-tools
        
        pip install pip-tools
        
* Install all dependencies from the "requirements.txt" file:

        pip-sync
        
* If you want to deactivate the virtual env:
        
        deactivate

### 3. Install all packages just with pip - without Virtual Environment (OPTION 2 - Easier)

* Go to the project folder and install all dependencies:

        pip install -r requirements.txt
        




Thats it

just text in chat if you need help on anything!
remember, this project is just for fun. no one has any obligations and responsibilities

-ryan



