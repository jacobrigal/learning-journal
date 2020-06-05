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

+ Add a file to the index (local repo):

      git add [file name]

+ Commit a file to the global repo: 

      commit [file name]

+ Publish the files in your local repo to the global repo:
          
      git push

+ Merge versions:
    
      git merge 

+ Show modified files yet to be added to the cloud, status of your local branch compared to master branch: 

      git status 

+ Restore previous version of a file in the working directory on your local machine: 

      git restore [file]

+ Get help (commands start with lower case): 

      $ git help
      usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

      These are common Git commands used in various situations:

      start a working area (see also: git help tutorial)
      
      clone             
      Clone a repository into a new directory
      
      init              
      Create an empty Git repository or reinitialize an existing one

      work on the current change (see also: git help everyday)
       
      add               
      Add file contents to the index
      
      mv                
      Move or rename a file, a directory, or a symlink
      
      restore           
      
      Restore working tree files
      
      rm                
      Remove files from the working tree and from the index
      
      sparse-checkout   
      
      Initialize and modify the sparse-checkout

      Examine the history and state (see also: git help revisions)

      bisect            
      Use binary search to find the commit that introduced a bug
      
      diff              
      Show changes between commits, commit and working tree, etc

      grep              
      
      Print lines matching a pattern
      
      log               
      Show commit logs
      
      show             
      Show various types of objects
      
      status            
      Show the working tree status

      grow, mark and tweak your common history
      branch            
      
      List, create, or delete branches
      
      commit            
      Record changes to the repository
     
      merge             
      Join two or more development histories together
      rebase            
      Reapply commits on top of another base tip
      
      reset             
      Reset current HEAD to the specified state
      
      switch            
      Switch branches
      
      tag               
      Create, list, delete or verify a tag 
      object signed with GPG
      collaborate (see also: git help workflows)
      
      fetch             
      Download objects and refs from another repository
      
      pull             
      Fetch from and integrate with another repository or a local branch
      
      push              
      Update remote refs along with associated objects
