Open Git Bash on Git 
"mkdir git-assignment
cd git-assignment"
And initialise the assignment
"git init"

Create readme with

echo "CSCI-3323 FALL 2024
Git Assignment
Kundan Thonda" > README.md

Create STEPS.md and commit with

git add README.md STEPS.md
git commit -m "Commit 0: Initial commit"

Repeat this step for commit 2

Before step 3, lets create a new branch using

git checkout -b bug-fix

And do the 3rd commit 

and check back to master using 

git checkout master

Created another Branch-experimental
Merged that with bug fix first and then with Main