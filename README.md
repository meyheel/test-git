# CODEOWNERS   
.github/CODEOWNERS  
/** @meyheel  
/* @meyheel  
.gitignore @meyheel  

# test-sparse-checkout in windows

git clone --no-checkout https://github.com/meyheel/test-git

cd test-git

C:\test\test-git>git sparse-checkout list
fatal: this worktree is not sparse

git sparse-checkout init

git sparse-checkout set B

git sparse-checkout list

git sparse-checkout set B/b/1.txt

git sparse-checkout list

git sparse-checkout add a

git sparse-checkout list

git checkout


test
