# github-docs

## Git : fatal: Could not read from remote repository. Please make sure you have the correct access rights and the repository exists


// 1. generate ssh key

ssh-keygen -t ed25519 -C "debra4117@gmail.com"

// 2. paste the key

clip < ~/.ssh/id_ed25519.pub

// 3.paste in git hub git setting

// 4. 

git remote set-url origin https://github.com/52147/1.git

// 5.
git push
