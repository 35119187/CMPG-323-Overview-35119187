# CMPG-323-Overview-35119187
This is the repository for project 1. It provides an overview and planning of my work will be managed throughout the semester.

## Project Repositories

<b> Project 1 </b>
<li> CMPG 323 Overview-35119187-https://github.com/35119187/CMPG-323-Overview-35119187.git</li></a>

<b> Project 2 </b> 
<li> CMPG 323 Project 2-35119187-https://github.com/35119187/CMPG-323-Project2-35119187.git</li></a>

<b> project 3 </b>
<li> CMPG 323 Project 3- 35119187-https://github.com/35119187/CMPG-323-Project3-35119187.git</li></a>

<b> project 4 </b>
<li> CMPG 323 Project 4- 35119187-https://github.com/35119187/CMPG323-Project4-35119187.git</li></a>

<b> project 5 </b>
<li> CMPG 323 Project 5- 35119187-https://github.com/35119187/CMPG-323-Project5-35119187.git</li></a>

## Repository Explaination

There will be only one project that contains repositories for every project in this module
![Diagrams](https://user-images.githubusercontent.com/91702944/184996761-eaaafd82-bc0f-4784-bf39-a3aca3974dff.PNG)


# Branching strategy
To allow my files to be copied to other directories, branches will be used instead of having to copy from directory to directory.

<li>Each project will have a main branch to store the code and final product</li>
<li>There will be develop sub-branch that will be directly created from main branch</li>
<li>Changes will be made in develop branch without affecting the code in main branch</li>
<li>Every feature created will be named and have a proper description</li>
<li>After each and every change in the branch the push command will be used to commit all the changes to the repository</li>
<li>To apply all the changes to the main branche pull request will be opened and merge the code to the main branch</li>

## Management of projects version control

## <b>Use of Git Command</b>

<li>Git command will be the oe assisting in updating all the final changes that have been made on local repository to the remote repository.</li> 
<li>To ensure that the github project is up to date, the remote repository will be cloned to local using the git clone command.</li>
<li>To keep track of all the changes that have been made on the projects, git status will used to check for files and changes staged and unstaged.</li>
<li>To add changes that have been made, to avoid losing importatant work, git add command will specify which changes within the projects to put to the stage area.</li>
<li>Once the changes have been added to the staged area, will be moved to the local repository using git commit.</li> 
<li>The project changes that have been moved to the local repository will be uploaded to the remote repository using the push command</li>


# The use of gitignore file
To avoid files that are not important to be generated to the repository the gitignore file will be used.
It will be used to not track generated files from project code  and don't upload them to the project repository
The size of repository will be reasonable and it will have less issues

# Storage of Sensitive Information and credentials

Sensitive information and credentials about my project will secured using github secret in management tool, to avoid them being leaked to where they will be vulnearable to attacks.

The secret feature will be enabled in the management tool to store all my sensitive information such as credentials, API keys and public profile of my web app.
The secret will help to encrypt my data before it reachces my github and make sure that it remain encrypted until being ready to be used 

