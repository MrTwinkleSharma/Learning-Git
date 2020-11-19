# Tutorial
### Installing and Getting Started
- Install Git 

- After Installing Git set your identity
```
git config --global user.name  "Twinkle Sharma"
git config --global user.email "smtwinkle451@gmail.com"
```
- View Identity at any time
```
git config --global user.name  
git config --global user.email
```


- Initializing Git Repository
```
git init
```
```git init``` turns any directory into a Git repository, it is used to initialize git repository, Git creates a hidden directory called .git. 
That directory stores all of the objects and refs that Git uses and creates as a part of project's history. 
This hidden .git directory is what separates a regular directory from a Git repository.
use ```ls -lart``` to verify this .git folder has been created.
