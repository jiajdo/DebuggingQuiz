![image](https://github.com/jiajdo/DebuggingQuiz/assets/127568197/fef1216a-aeee-4628-92fa-8ee53edddc13)


## Week 14 Quiz - Debugging, Git, & GitHub

Moved files for correct file architecture using ```mv``` 
Made server directory with ``mkdir`` 

## Removing node_modules

Added node_modules folder with ``**/node_modules``

Removed cached node_modules with ```git rm -r --cached node_modules```

Commit git repo without node_modules ```git commit -m Commit message```

Push the change ```git push origin main```

Commit ```.gitignore```

```git add .gitignore \ git commit -m commit message\ git push```

I also had to delete and re-install ``packagelock.json`` files at every level and redid ``npm install`` for frontend server to work. 


1. Debug the broken code so that it's working
2. Correct the file architecture using command line
3. node_modules are committed, remove them from repo on GitHub
4. Correct the server file’s directory by moving it to the appropriate directory
5. Update README with
    - screenshot of the app's webpage, 
    - document errors you encountered and how you fixed them, 
    - detail the git commands you used to remove the node_modules, and
    - detail the git commands you used to correct the file structure
