# skill_captain_git

<!-- Create a new Git repository locally. -->
  * skill_captain_git create this repository.

<!-- Implement the feature branch strategy by creating a branch named "feature-login" and another branch named "feature-logout". -->
    git branch feature-login
    git branch feature-logout

<!-- Make changes related to the login functionality in the "feature-login" branch and changes related to the logout functionality in the "feature-logout" branch. -->
    create a login.html and logout.html in this two branches.

<!-- Commit your changes and push the branches to a remote repository. -->
    git commit -m"#comment"
    git push origin feature-login
    git push origin feature-logout

<!-- Create a new branch named "develop" from the main branch -->
    git branch develop

<!-- . Make additional changes and commits related to both login and logout functionality in the "develop" branch. -->
    make small change and commit with `git commit -m"#comment"` with this command 

 <!-- Push the "develop" branch to the remote repository. -->
    # Switch to main branch
   git checkout main

   # Merge the changes from develop
   git merge develop

   # Push the changes to remote main branch
   git push origin main


# Pull Requests and Code Reviews:
<!-- a. Fork the repository of a fellow classmate or a public repository on a Git hosting platform (e.g., GitHub). -->
    git clone https://github.com/RushiRaj-001/fork_repo.git
  
  
<!-- Create a new branch in your forked repository and make changes to fix a bug or add a new feature -->

# Create and switch to a new branch
git checkout -b fixed

# Make changes based on feedback
git add .
git commit -m "Change Var to String"

# Push changes to your branch in your forked repository
git push origin fixed

<!-- 4. Working with Upstream Repositories:

a. Find an open-source project on GitHub. -->
find this opensource "html5-boilerplate"

# Add the upstream remote
git remote add upstream https://github.com/h5bp/html5-boilerplate.git

<!-- Fetch the latest changes from the upstream repository. -->

 git fetch upstream