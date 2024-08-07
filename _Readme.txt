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
git init

git status

git add .					// all folders and files
git add src				// all folders and files under src

git commit -m "version1" 	// commit with message version1

git commit -m "version1" --amend 	// commit as one before with amend

git reset .			// get out from staging aera
git log
