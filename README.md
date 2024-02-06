# Git Activity

The goal of this activity is to practice pushing and pulling from GitHub. Cloning a repository from github is crucial for you to be able to work on code stored on a remote repository, and similarly, pushing code is equally as important for taking your local changes and storing them on GitHub. You'll use the following activity to practice this. See the file `bryan-serfozo.txt` for an example.

## Instructions

1. Open a gitbash window wherever you want this repository to live, if you want it in your Documents folder, make sure the yellow text in your GitBash window says something along the lines of `~/Documents`. If it doesn't say that, navigate it to there.

2. In the GitBash window, paste the following command: `git clone https://github.com/240205-JavaAngularAWS/git-activity.git` as this should copy the remote repository to your personal computer.

3. Either through the file explorer or using bash commands, create a new file called `firstname-lastname.txt` with your first name and last name. Open the file, add a fun fact about yourself that you want everyone to know and then save and close it.

4. Now that we have our "code" written, we need to push it to the remote repository. Before we do that, we should make sure we have the most current code from the remote repo (if somebody else pushed some code to main, it can cause our versions to be out of sync), to do this, return to the GitBash window from before and use the cd commands to make sure you're in the right directory. It should be something along the lines of `cd git-activity`, after this, we'll run a `git pull` to pull the most recent changes from the repository.

5. Now that we have the most current code, we should be able to begin the process of pushing. First run the command `git add .` to add all the changes from the working directory to the staging area. **NOTE** Don't forget the . at the end of `git add .`

6. After that, we'll commit our changes and have them ready to be pushed. Commit the changes with the following command `git commit -m "Change me to a good commit message"` and don't forget to update the message to something short, concise, and representative of the changes you've made with this push. **Note** You may receive a notification or popup (either on this step or the next) letting you know that you need to sign in, attempt to follow the commands given in the GitBash window to log in via the Git Credentials Manager (this will allow git to know it was you who made the changes and not a different account)

7. Now we can finally push our code up using the `git push` command. Run this, make sure it successfully completes (again you may need to log in if you haven't already, keep an eye out for anything asking you to sign into github), and if it does so, you should be able to refresh the github page and see that your file was pushed!