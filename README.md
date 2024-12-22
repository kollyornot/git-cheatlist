SSH - Secure Shell - one of the most popular network protocols (when pcs exchange data, they follow network protocols - rules of exchanging data between pcs)
fork - gihub tool which allows you to work on public code without it being synchronised to original one

change directory - cd
check what is in directory - pwd 
initialise git repository - git init
undo git repository - rm -rf .git (deletes .git directory)
check repository - git status
add file to commit it - git add [file-name% (if all -  git add —all)
commit a file - git commit ( to add a message to a commit [-m ‘ ’])
push a commit to a remote git - git push (first time git push -u origin main)
check commit history - git log 
generate SSH pair -  sh-keygen -t ed25519 -C "электронная почта, к которой привязан ваш аккаунт на GitHub" 
check if keys had been created -  ls -a ~/.ssh
connect SSH-key and GitHub acc - pbcopy < ~/.ssh/id_ed25519.pub
connect remote repository to local - cd [your repository] && git remote add origin [link from github]
check if repositories are connected - git remote -v
clone repository - git clone [url]
 


you have 2 keys(SSH) - one that encrypts your data, public one, and one that decrypts your data, it should not be given to anybody!!!11!!!!1!!!!!111!



git add [file name/—all] —>  git commit -m [message to a commit] — > git push