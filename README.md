# github-docs

## Git : fatal: Could not read from remote repository. Please make sure you have the correct access rights and the repository exists
Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

// 1. generate new ssh key

ssh-keygen -t ed25519 -C "xxxx@gmail.com"

// 2. paste the key

clip < ~/.ssh/id_ed25519.pub

// 3.paste in git hub key setting

// 4. 

git remote set-url origin https://github.com/52147/1.git

// 5.

git push


##  ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/52147/1.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

1. git fetch
2. git pull <https://github.com/52147/Interview-Question.git>
3. git push 
