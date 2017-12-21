# Git Basic Concepts


# Check if Git has already been installed
git --version

# Add your Git username
git config --global user.name "YOUR_USERNAME"

# Add your Git email address
git config --global user.email "your_email_address@example.com"

--global
If you want to override this with a different username or email address for specific projects, you can run the command without the --global option when you’re in that project

# Check your information
git config --global --list

Adding an existing project to GitHub using the command line

# Step1 : Go to the below URL for creating a new repository on GitHub.
https://github.com/new
Then enter your repository name, Click on create repository button

# Step2 : Open command line, Change the current working directory to your local project then run the below command one by one 

git config --global user.email "usermail@gmail.com"

git config --global user.name "username"

git init

git add .

git commit -m "first commit"

git push -u origin master 

# Example
```
git init
git clone {repository url}
git checkout -b {branch_name}
git add .
git commit -m "first commit"
git push origin {branch_name}
```

# Get starting from scratch
```
git clone {repository url}
cd widget
echo "# My project's README" >> README.md
git add README.md
git commit -m "Initial commit"
git push -u origin master
```
