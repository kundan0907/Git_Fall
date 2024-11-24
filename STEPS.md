# Open Git Bash and execute the following commands

# Create and navigate to the project directory
mkdir git-assignment
cd git-assignment

# Initialize the Git repository
git init

# Create README.md with assignment information
echo "CSCI-3323 FALL 2024
Git Assignment
Kundan Thonda" > README.md

# Create an empty STEPS.md file
touch STEPS.md

# Stage and commit initial files (Commit 0)
git add README.md STEPS.md
git commit -m "Commit 0: Initial commit"

# Edit README.md for Commit 1 (make your changes here)
echo "Adding content for Commit 1" >> README.md

# Stage and commit changes (Commit 1)
git add README.md
git commit -m "Commit 1: Add changes to README.md"

# Edit README.md for Commit 2 (make your changes here)
echo "Adding content for Commit 2" >> README.md

# Stage and commit changes (Commit 2)
git add README.md
git commit -m "Commit 2: Add more changes to README.md"

# Create and switch to bug-fix branch
git checkout -b bug-fix

# Edit README.md for Commit 3 (make your changes here)
echo "Adding content for Commit 3 in bug-fix branch" >> README.md

# Stage and commit changes (Commit 3)
git add README.md
git commit -m "Commit 3: Add changes in bug-fix branch"

# Switch back to master branch
git checkout master

# Create and switch to bug-fix-experimental branch
git checkout -b bug-fix-experimental

# Edit README.md for experimental changes (make your changes here)
echo "Adding experimental content" >> README.md

# Stage and commit experimental changes
git add README.md
git commit -m "Experimental: Add experimental changes"

# Switch back to bug-fix branch
git checkout bug-fix

# Merge bug-fix-experimental into bug-fix
git merge bug-fix-experimental

# Resolve any merge conflicts if they occur, then stage and commit resolved files

# Switch back to master branch
git checkout master

# Merge bug-fix into master
git merge bug-fix

# Resolve any merge conflicts if they occur, then stage and commit resolved files

# Add a chill guy meme image to the repository (assuming you have a file named chill_guy.jpg)
cp /path/to/chill_guy.jpg .
git add chill_guy.jpg
git commit -m "Add chill guy meme image"

# Open GitHub Desktop, push, and publish all branches to GitHub