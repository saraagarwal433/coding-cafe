Question 1

--global means that the name and email settings will be used for all the Git repositories on my computer. If I leave it out, the settings will only apply to the repository I am currently in.

Question 2
`.git` appeared in `ls -a` but not in `ls`. It is a hidden folder that Git created when I ran `git init`, and it stores the information Git needs to manage the repository.
Question 3

There were roughly 8 files and folders listed. .venv/ stood out because it contains code and files that I did not write myself.

Question 4

.venv/ disappeared from the list after creating .gitignore. Git now ignores it because .venv/ was added to the .gitignore file.

Question 5

.gitignore should be committed because it is part of the project and tells Git which files and folders to ignore. It should not be ignored itself because other people working on the project also need these rules.

Question 6

Before, README.md was listed under Untracked files. After running git add README.md, it moved to Changes to be committed, which means Git has prepared it to be included in the next commit.

Question 7

Git created the first commit called Lab work so far. It said that 8 files were changed and that there were 227 insertions.

Question 8

The first seven characters of my commit are 9730aab. They are a shortened version of the commit's hash, which Git uses to identify that particular commit.
 Question 9 
The four steps are: create or edit a file, check the status, add the changes to the staging area, and commit the changes. I repeated this process for the first two commits. 
 
Question 10 
`README.md` has a special name because it is the main file people see when they open a repository. It gives an overview of the project and its contents, while `notes.md` is just a regular file for my notes. 
 
Question 11 
`gh auth login` connected my GitHub account to Git on my computer. After I authenticated through the browser, GitHub CLI could handle authentication for me, so I did not have to enter my password every time I pushed. 
 
Question 12 
The files from my local repository are now shown on the GitHub front page because I pushed my commits to the GitHub repository. 
 
 Question 13 
No, pushing did not change my local history. It only uploaded my existing commits to GitHub. 
 
Question 14 
A private repository can only be accessed by people who have been given access to it, while a repository that is not on GitHub cannot be accessed there at all. I invited the three TAs as collaborators so they can access the private repository.
