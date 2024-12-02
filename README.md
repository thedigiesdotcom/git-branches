# Git Branches

## Clone a Repository
First, clone an existing repository to your local machine. Open your terminal and run:
git clone https://github.com/YourUsername/YourRepository.git

## Navigate to the Repository
Change your directory to the cloned repository:
cd YourRepository

## Check Current Branch
Before creating a new branch, check which branch you're currently on:
git branch

## Create a New Branch
Create a new branch named `feature-branch`:
git checkout -b feature-branch

## Make Changes
Open the project in your preferred text editor and make some changes. For example, you might edit a file called `README.md`.

## Add and Commit Changes
After making your changes, add them to the staging area and commit them:
git add README.md
git commit -m "Updated README in feature-branch"

### Made changes in README.md
and committed to feature-branch

## Push Changes to Remote
Push your changes to the remote repository:
git push origin feature-branch

## Merge the Branch (Optional)
If you're satisfied with the changes in `feature-branch`, you can merge it into the `main` branch:
git checkout main





