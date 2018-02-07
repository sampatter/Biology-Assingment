## Learning github for Fun!

- Q1. When should you use Git for a project?

- A1. git is an exllenct tool for programmers and biologists working with larger data sets or collrabrative projects. This platform allows many collaborators to access a project, such as a pice of code, and provide changes and comments. However version control is avaliable for projects, this means that moderators or collabroators will have a historical record of past versions and there changes. git hub tracks changes between collabroators on a project and is espicially usefull when many vbersions of the same project are being consitently modified. A good rule of thumb for this question is "if you would be upset to loose the work - store it on github". 


- Q2. What kind of files/info should be saved in a Git repository? What types of files/info should not be included in a Git repo?

- A2. github is a freesoftware and open access, this means that confedential information or data is best left of this server. uploading data to github is something that you must be sure of before you commit, as once it is pushed to the internet, you run the risk of someone copying or forking the data. github is primarily used for people who upload code or text files to collborate on, these files are often not as sensitive as raw data or large in space. Extermelly large data sets cannot be upload to github due to storage requirments.  


- Q3. What are the commands to undo a commit?

- A3. A quick way to undo your last commit is the syntax $ git reset Head~1 which will restore the perivous version of your file before your last commit. This is useful if you make a quick mistake but still want to have the error you made included in your edit history. Chaning the number beside "Head~" will take you back multiple version numbers. 

- Q4. One of your repositories is in a “detached HEAD” state. How do you fix this?

- A4. 
