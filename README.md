# 3.2_git_exercise

## Assignment submission

#### What is GitHub Authentication and how what methods available to be implemented?

```
GitHub Authentication refers to the process of verifying the identity of users accessing GitHub, a web-based platform for version control and collaboration on software projects. It allows users to securely access and interact with repositories, issues, pull requests, and other features provided by GitHub.

GitHub provides several authentication methods that can be implemented to ensure secure access to user accounts and resources. Here are some of the available methods:

1. Username and Password: This is the traditional method where users provide their username and password to authenticate themselves. However, it is generally recommended to use more secure methods like OAuth or personal access tokens instead of using passwords directly.

2. OAuth: OAuth (Open Authorization) is an industry-standard protocol for authorization. It allows users to grant access to their GitHub accounts to third-party applications without sharing their passwords. GitHub supports OAuth 2.0, and developers can integrate it into their applications to enable users to sign in using their GitHub accounts.

3. Personal Access Tokens (PATs): Personal access tokens are alternative authentication credentials that can be used instead of passwords. Users can generate personal access tokens in their GitHub account settings and use them to authenticate API requests or command-line access.

4. SSH Keys: Secure Shell (SSH) keys provide a way to authenticate and establish a secure connection between a user's local machine and GitHub. Users can generate an SSH key pair and add the public key to their GitHub account. This method is commonly used for secure repository cloning, pushing, and pulling over SSH.

5. GitHub Apps: GitHub Apps are integrations that can be installed directly on GitHub accounts or organizations. They can authenticate and interact with GitHub on behalf of users or organizations. GitHub Apps use their own authentication flow, and developers can configure the permissions they require.

6. SAML Single Sign-On (SSO): GitHub supports SAML (Security Assertion Markup Language) SSO, which allows organizations to use their existing identity provider (IdP) to manage authentication and access control. This method enables users to sign in to GitHub using their organization's credentials.

These authentication methods provide flexibility and security for accessing GitHub accounts and resources based on different use cases and requirements. Developers can choose the most suitable method based on the application they are building and the needs of their users.
```

#### 15 Github commands

|No.| Command | Usage |
|---|---|---|
| 1 | git clone | is used for just downloading exactly what is currently on the remote repository and saving it in your machine's folder where that project is placed  (Only one time)|
|2| git fetch | s the command that tells the local repository that there are changes available in the remote repository without bringing the changes into the local repository.|
|3| git pull | downloads the changes and merges them into your current branch. (Can be multiple time if there is new changes on the branch in the repo). |
|4| git add .| Stage the all the file for commit to your local repository by the following command.|
|5| git commit -m "*comments*"|Commit the file that you’ve staged in your local repository.|
|6| git push origin main | Push the changes in your local repository to GitHub.|
|7| git branch | Check current branch in Github |
|8| git branch *name* | create new branch |
|9| git checkout *name* | Change to the new branch |
|10| git checkout -b *new-branch-name* | create new branch and change to the branch |
|11| git push --set-upstream orgin *new-branch-name* | first time push to the new branch |
|12| git status | show modified files in working directory, staged for the next commit |
|13| git reset [file] | unstage a file while retaining the changes in working directory|
|14| git merge [branch]|merge the specified branch's history into the current one|
|15| git log | shows all commits in the current branch's history|


[*source*] 
- *Slide 3.1 Introduction to GIT* (https://docs.google.com/presentation/d/1fBuWjR94G7T86DJOH100DnufQihoBXY0O-YHqEhqk_0/edit#slide=id.g228027d5e89_0_145)
- *Git Cheat Sheet* (https://education.github.com/git-cheat-sheet-education.pdf)

### What are the 4 Github commands that you think you will use the most in the real project and why? Explain it on the readme file.

1. *Git add .* 
```
We need this command to add all the files in the local repository to be pushed into Github.   
```

2. *git clone*
```
Download the github repo locally so that we can work on it.
```

3. *git commit -m "comments"*
```
Stage the local files to be pushed into Github repo
```

4. *git push*
```
Pushes the local repo into github repo
```
