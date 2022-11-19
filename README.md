## MLopsbostonhousepricing Demo project for student

## software and tools requirements 

1. [GitHub Account](https://github.com) 
2. [VS Code IDE](https://code.visualstudio.com/)
3. [Heroku Account](https://heroku.com)
4. [GitCLI](https://git-scm.com/downloads)

Create a new enviroment
`````````
conda  create -p venv python=3.9 -y
`````````

Activate enviroment
``````
conda activate venv/
````````````

Create requirements.txt and install all required liabry
``````
pip install -r requiremets.txt
```````

## push into github: Steps
``````
git config --global user.name "your git name"
git config --global user.email "your git email"
``````
1. Add file to git and check
``````
git add filename 

//OR to add all files//

git add .
``````
2. [Git Commit Command Link](https://www.atlassian.com/git/tutorials/saving-changes/git-commit)
`````
git commit -m "This is first commit; includes requirements.txt and readme file"
```````
3. [Git Push Command Link](https://www.atlassian.com/git/tutorials/syncing/git-push#:~:text=The%20git%20push%20command%20is,exports%20commits%20to%20remote%20branches.)

`````````
git push origin main 
`````````