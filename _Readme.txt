Git and GitHub
-------------------------------------------------------------------
Install git form website download
run command under Windows PowerShell


> git 
--will show usage:

Run
>git config --global user.email "chen.klaus@hotmail.com"
>git config --global user.name "klaus.chen"

make sure into the right folder
cd\projects\_Tutorial\git-tutorial

in VS Code
select Terminal under menu View

PS E:\Projects\_Tutorial\git-tutorial>

1. Create a Version
git init
git status
git add .						// all folders and files
git add src					// all folders and files under src
git commit -m "version1" 					// commit with message version1
git commit -m "version1" --amend 	// commit as one before with amend

2. View Previous Versions
git log --all --graph
git checkout <commit_hash>
git checkout <branch_name>

3. Restore to Previous Version
git checkout <hash|branch> <folder|file>
git commit -m "Message"

git reset .				// get out from staging aera
git checkout -- .	// reset all changes back to 
git checkout ea5f69080a7eb405002c9c1e03a78eedf5521cff
git checkout master
-- Restore src backto version1 (b85f2feb81087729d9f7d70fb7985d64848b3ea4)
git checkout b85f2feb81087729d9f7d70fb7985d64848b3ea4 src

git log --all --graph

alias
git config --global alias.s "status"
git config --global alias.cm "commit -m"
git config --global alias.co "checkout"

rmove all git from project
rm -rf .git