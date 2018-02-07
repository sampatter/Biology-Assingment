## Learning github for Fun!

- Q1. When should you use Git for a project?

- A1. git is an excellent tool for programmers and biologists working with larger data sets or collaborative projects. This platform allows many collaborators to access a project, such as a piece of code, and provide changes and comments. However, version control is available for projects, this means that moderators or collaborators will have a historical record of past versions and their changes. git hub tracks changes between collaborators on a project and is especially useful when many versions of the same project are being consistently modified. A good rule of thumb for this question is "if you would be upset to lose the work - store it on GitHub". 


- Q2. What kind of files/info should be saved in a Git repository? What types of files/info should not be included in a Git repo?

- A2. github is a free software and open access, this means that confidential information or data is best left of this server. uploading data to github is something that you must be sure of before you commit, as once it is pushed to the internet, you run the risk of someone copying or forking the data. github is primarily used for people who upload code or text files to collaborate on, these files are often not as sensitive as raw data or large in space. Extremely large data sets cannot be upload to github due to storage requirements.  


- Q3. What are the commands to undo a commit?

- A3. A quick way to undo your last commit is the syntax $ git reset Head~1 which will restore the pervious version of your file before your last commit. This is useful if you make a quick mistake but still want to have the error you made included in your edit history. Channing the number beside "Head~" will take you back multiple version numbers. 

- Q4. One of your repositories is in a “detached HEAD” state. How do you fix this?

- A4. Detached head state is a common problem that users of github may encounter. This problem happens when the changes of your most recent file don’t have a destination to go to. To get out of detached Head state, use the syntax $ git checkout master, this will re-attach the head, and allow you to exit the detached head state. Alternatively using the command git check out -, will check out the last branch you check and reattach your head.

- Q5. Your boss has no idea what Git is or why you are using it. a) Explain the pros / cons of using Git for your research project. b) Explain the pros / cons of hosting your project in a public (or private) repository on Github/Bitbucket/GitLab/etc.

- A5. 

Pro
>> Remote access to files and projects with wife access. 
>> Total back up for files and version control.
>> Access to international resources. 
>> Low cost and free access for basic functions. 
>> Produce high quality publications and projects. 
>> Potential for collaboration.

Con 
>> Public access repositories and project materials stored in online server - security risk. 
>> Learning curve for new users and non-tech savvy workers. 
>> github limits the size of files that may be uploaded. 

Public vs Private - Pros and cons
>> Collocation by other users, and easy access for multiple users - Public 
>> Anyone can access your work - Public 
>> Cost associated with Service - Private 
>> Can open networking options - Public 
>> Storage limits - Public
