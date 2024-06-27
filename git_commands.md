# Initializing a repository
git init

# Cloning a repository
git clone <repository_url>

# Staging changes
git add <file_name>
git add .

# Committing changes
git commit -m "Commit message"

# Checking status
git status

# Viewing commit history
git log

# Creating a new branch
git branch <branch_name>

# Switching to a branch
git checkout <branch_name>

# Merging branches
git merge <branch_name>

# Pushing changes to a remote repository
git push <remote_name> <branch_name>

# Pulling changes from a remote repository
git pull <remote_name> <branch_name>

# Fetching changes from a remote repository
git fetch <remote_name>

# Creating and applying patches
git diff > patch.diff
git apply patch.diff

# Reverting changes
git revert <commit_hash>

# Discarding local changes
git checkout -- <file_name>

# Removing files from the repository
git rm <file_name>

# Renaming files
git mv <old_file_name> <new_file_name>

# Configuring Git
git config --global user.name "Your Name"
git config --global user.email "your@email.com"