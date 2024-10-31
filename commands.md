Preparation
Create Directory (mkdir): mkdir git-for-devops
List Directory Contents (ls): ls
Navigation

Change Directory (cd): cd git-for-devops/
Verification

List Directory Contents (ls): ls
Print Working Directory (pwd): pwd
Initialization

Initialize Git Repository (git init): git init
List Directory Contents (ls): ls (Shows hidden files with ls -a)
Show All Files (ls -a): ls -a
Status

Check Repository Status (git status): git status
Adding Files

Create New Files (touch): touch nibba.txt nibbi.txt
List Directory Contents (ls): ls
Check Repository Status (git status): git status (Shows new files)
Staging & Unstaging

Add Files to Staging (git add): git add nibba.txt nibbi.txt
Check Repository Status (git status): git status (Shows staged files)
Unstage a File (git rm --cached): git rm --cached nibba.txt
Check Repository Status (git status): git status (Shows nibbi.txt staged)
Restoring

Re-add File to Staging (git add): git add nibba.txt
Check Repository Status (git status): git status (Shows both files staged)
Committing

Commit Changes (git commit): git commit -m "hey there" nibba.txt nibbi.txt
User Setup (Optional)

Set Global User Info (git config):
git config --global user.email "piyushdoifode05@gmail.com"
git config --global user.name "piyushdoifode"
Further Commit (Optional - Doesn't Work)

Attempt Another Commit (git commit): git commit -m "hey there" nibba.txt nibbi.txt (Won't work without changes)
Verification & Removal

List Directory Contents (ls): ls
Check Repository Status (git status): git status
Remove File from Disk (rm): rm -rf nibba.txt (Use with caution!)
Check Repository Status (git status): git status (Shows deleted file)
Restore from Staging

Restore File from Staging (git restore): git restore nibba.txt
List Directory Contents (ls): ls (File not restored to disk)
Check Repository Status (git status): git status (Shows deleted file)
Restore Attempt (Won't Work)

Attempt Restore Again (git restore): git restore nibba.txt (Won't work as it's not staged)
Check Repository Status (git status): git status (Shows deleted file)
Final Verification

List Directory Contents (ls): ls (File remains deleted)
