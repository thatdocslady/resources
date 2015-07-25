### Activating virtualenv
- Windows:  
`myvenv\Scripts\activate`
- OSX/Linux:   
`source myvenv/bin/activate`
(or `. myvenv/bin/activate`)

### Django manage commands
- Create new migrations:  
`python manage.py makemigrations blog`
- Apply migrations:  
`python manage.py migrate blog`
- Start web server:  
`python manage.py runserver`
- Open Django's Python console:  
`python manage.py shell`...
- ...and exit it: `>>> exit()`


### Git
- See which files you've changed and what's been added in git:  
`git status`  
- Add one file:  
`git add <file>`
- Add all new/modified files from current directory:  
`git add .`  
- Add all files (new/modified and deleted) from current directory:  
`git add -A .`  
- Save changes to git's commit history:  
`git commit -m "message"`  
