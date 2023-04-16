# CODEOWNERS   
.github/CODEOWNERS  
/** @meyheel  
/* @meyheel  
.gitignore @meyheel 

"# Lines starting with '#' are comments."
"# Each line is a file pattern followed by one or more owners.

# More details are here: https://help.github.com/articles/about-codeowners/

# The '*' pattern is global owners.

# Order is important. The last matching pattern has the most precedence.
# The folders are ordered as follows:

# In each subsection folders are ordered first by depth, then alphabetically.
# This should make it easy to add new rules without breaking existing ones.

# Global rule:
*           @dotnet/docs

# C# samples:
/csharp/**  @BillWagner

# ML.NET samples:
/machine-learning/**  @luisquintanilla

# WPF folders:
/wpf/**   @adegeo

# Windows forms areas:
/windowsforms/** @adegeo @dotnet/dotnet-winforms

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
