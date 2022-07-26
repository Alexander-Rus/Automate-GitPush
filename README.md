<!-- AUTO-GENERATED-CONTENT:START (STARTER) -->
<p align="center">
    <img alt="Gatsby" src="https://upload.wikimedia.org/wikipedia/commons/8/82/Gnu-bash-logo.svg" width="60" />
</p>
<h1 align="center">
  Simply Bash Script to Automate Git pushes
</h1>

I find it tedious to consitantly have to type commit statements, add files, and then push. I understand that best coding practice asks a developer to use detailed commits that explain each code change, but I often find it difficult to remember what commit messages I have made.

In my opinion, it is easier to keep track of commits by the time and date at which they were commited, as I can then checkout versions based on time, rather than based on arbirary message.

Therefore, I have made this simple bash script for Ubuntu, where you can simple call the script and it will add changed files, add a commit message with the date and time, and then push to the master branch.

In the future I may add additional functionality, but for now this is simple and keeps my git pushes consistent and quick.

## 🚀 Quick start 

1.  Clone this repository to your local machine. 

    You won't need the README.md file, that is just a description file.
    
    To make the bash script executable you need to type `chmod +x gitpush.sh`.
    
    You can then call the script by typing ./gitpush.sh

    **Note**: You must first set up the repo in github, and have your local machine pushing to the main branch for this script to work. Github provides a list of steps to take to initate a repository, but if you forgot here they are:
        ```script
	echo "# Automate-GitPush" >> README.md
	git init
	git add README.md
	git commit -m "first commit"
	git branch -M main
	git remote add origin git@github.com:Alexander-Rus/Automate-GitPush.git
	git push -u origin main
	```
 
