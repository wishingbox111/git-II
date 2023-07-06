### git-II

# Assignment for 3.2 Introduction to Git II

### Brief
- You have learned on how to create new repository and create the changes on it. For the assignment, create new repository named with professional naming that you want.
- On the readme file, explain what is GitHub Authentication and how what methods available to be implemented?
- Update the Readme file to contain least 15 github commands and what are the usage of them?
- What are the 4 Github commands that you think you will use the most in the real project and why? Explain it on the readme file.
- Create your ReadMe.md file as professional and beautifull as possible. (https://dillinger.io/)
- Push the changes you made to your repository. with different commit.

## Submission
**GitHub Authentication** - is to authenticate autorised access to Github by securing the access to the account.

When you authenticate to GitHub, you supply or confirm credentials that are unique to you to prove that you are exactly who you declare to be.

The methods to authenticate:
- In the browser:
    - via GitHub Desktop:
         - Username and password
         - 2FA
    - another desktop application, with the API
    - via the command line:
         - Username and password with two-factor authentication
         - Personal access token
         - SSH key/HTTPS
     
  For Enterprise users of Github
  - in brower using IdP
  - SAML single sign-on
 
____________

**15 github commands & more** Also in https://github.com/wishingbox111/projectfolder-Enchen/blob/main/README.md


- `$ git init` To turn an existing directory into a git repository
- `git clone` is used for just downloading exactly what is currently on the remote repository and saving it in your machine's folder where that project is placed. (Only one time) 
- `git fetch` is the command that tells the local repository that there are changes available in the remote repository without bringing the changes into the local repository.
- `git pull` downloads the changes and merges them into your current branch. (Can be multiple time if there is new changes on the branch in the repo). 
- `git add .` Stage the all the file for commit to your local repository by the following command.
- `git commit -m` After creating changes on README file and to commit the file that you’ve staged in your local repository.
- `git push`  1)Push the changes in your local repository to GitHub.
              2)A pull request is an event in Git where a contributor asks a other member of a Git repository to review code they want to merge into a project.
- `git push origin main` 	Push the changes in your local repository to GitHub.
- `git status` List which files are staged, unstaged, and untracked
- `git branch` create new branch & also to check what are the branches in current branch you are in 
- `git checkout` Change to the new branch 
- `git checkout -b` create new branch and change to the branch (combination of the two code above)
- `git add .`
- `git commit -m “Comment of the changes”`
- `git push --set-upstream origin <new-branch-name>` - note <> should not be in the code
- `git push` push changes from local to github
- `git checkout main` to move back to main branch
- `git pull` as the main branch would have changed from last merge. To pull the changes into local folder.
- `git branch -d <name of branch>` to delete the branch when you are in the branch


**4 Github commands that I think I will use the most in the real project:**
- `git checkout -b` create new branch and change to the branch (combination of the two code above)
- `git add .`
- `git commit -m “Comment of the changes”`
- `git push --set-upstream origin <new-branch-name>` - note <> should not be in the code
  
*Reason of choose these 4 commands*
     
As I would most likely work on a branch to edit a file. Hence with every change, there'll be a need to create branch, add files to branch from local repo and commit and push it to be a complete cycle. 


## References
- https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-authentication-to-github
- https://git-scm.com/docs/pretty-formats - pretty formats
- https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax - all formats for Github
