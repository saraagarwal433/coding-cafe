Question 1

--global means that the name and email settings will be used for all the Git repositories on my computer. If I leave it out, the settings will only apply to the repository I am currently in.

Question 2

.git appeared in ls -a but not in ls. It is a hidden folder that Git created when I ran git init, and it stores the information Git needs to manage the repository.

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
