github!=git // for the rookies :>

How to clone something: git clone <repo link>
 
 How to clone a single branch in git: git clone --single-branch --branch <branch name> <remote link>

 Initialising git: git init
 
 Adding a file: git add README.md
 
 Adding all files: git add .
 
 Git commiting: git commit -m "Suitable message for the commit" 

 Always Commit after adding to git!
 
 Add remote to push the git commits to: git remote add [remote-name] [remote-link]
 
 For example:
      git remote add origin https://github.com/0x0elliot/newrepository.git
      
 Push into the remote link: git remote add [remote-name] [branch-name]
 
 For example:
      git push origin main
