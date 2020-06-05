## Revisions and the Cloud

Git is a version control system (VCS) originally developed by the chief architect of the Linux OS. It's fast and streamlined. A VCS allows for revisions to be tracked and saved, accessible for all team members, or even the public. Git allows for a distrubed VSC because local users can mirror the repositories on their own machines. This allows for recovery of data that is lost on the central server. Git also has strong corruption protection and data loss prevention. 

## Git Commands cheat sheet:
*this guide assumes you have installed git. 

*repo = github repository

+ Clone a repo to your local machine (makes an exact copy):

   Navigate to the directory you want the repo to reside in. 

   Enter the following command:

      git clone [full repo url]

+ Configure global user settings (using your github account):

      git config git config --global user.name "Your GitHub Username"` 

      git config --global user.email "emailyousignedupwith@love.yourself" 

+ Commit a file to the local repo (on your computer): 

      commit [file name]

 + Add a file to the global (shared) repository:

        git add [file name]

Push all commited local repo files to the master repo branch. 

+ add all the files in your local repo to the global repo:
          
      git push

+ Merge versions:
    
      git merge 

+ Show modified files yet to be added to the cloud, status of your local branch compared to master branch: 

      git status 

+ Restore previous version of a file in the working directory on your local machine: 

      git restore [file]