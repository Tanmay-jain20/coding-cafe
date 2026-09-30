1. --global tells Git where to save the setting. Using --global Git saves your name for your entire user account. So it will apply to all Git repositories you use on that computer. If you left it out Git sets the name only for the current repository.
2. ls -a showed an additional hidden .git and .venv files whereas ls showed the visible contents of folder i.e. lab 4, week 01, week02 and README. 
3. Git is offering to track 2 folders and a file. No, nothing in this list looks like something I did not write.
4. Nothing disappeared, because .venv was never listed in the first place. The only change is that .gitignore now appears as a new untracked file. It will hide __pycache__/, *.pyc and .DS_Store if they ever show up.
5. It should be committed. It's part of the project, it ensures everyone working on the project uses the same ignore rules. If it were ignored, nobody else would get those rules. 
6. README.md moved from Untracked files to Changes to be committed. In the three-places model, it went from the working directory to the staging area.
7. Git printed [master (root-commit) 30be6ad] Lab work so far and  5 files changed, 20 insertions(+). So 5 files changed in that commit. 
8. It's the short commit hash, an abbreviated version of the commit's unique ID. It's used to refer to one specific commit.
9. Four steps are: Check with git status, stage with git add, then save with git commit and check your commit with git log --oneline. I did that loop twice.
10. README.md is a convention, and GitHub looks for that exact name. It shows the file rendered on the repository's front page, so it works as the project's intro for anyone who visits.
11. It saved my GitHub credentials and set up Git to use them over HTTPS. So pushes authenticate automatically with no password prompt.
12. GitHub shows my README.md, rendered as formatted text. GitHub displays the README as the landing page by default.
13. No. Pushing copies my commits to GitHub and leaves my local history exactly as it was.
14. A private repository exists on GitHub, but only I and people I invite can see it. If it didn't exist there at all, there'd be nothing to share, so nobody, including the TAs, could ever be given access.


