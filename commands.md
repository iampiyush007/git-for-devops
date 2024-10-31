This guide walks you through a basic Git workflow using commands and explanations.

Preparation

Create Directory:
mkdir git-for-devops
List Directory Contents:
ls
Navigation

Change Directory:
cd git-for-devops/
Verification

List Directory Contents:
ls
Print Working Directory:
pwd
Initialization

Initialize Git Repository:
git init
List Directory Contents (including hidden files): This command (ls -a) shows hidden files like the Git repository files.
Status

Check Repository Status:
git status
Adding Files

Create New Files:
touch nibba.txt nibbi.txt
List Directory Contents:
ls
Check Repository Status: This shows the newly created files.
Staging & Unstaging

Add Files to Staging:
git add nibba.txt nibbi.txt
Check Repository Status: This shows the files added to the staging area (ready for commit).
Unstage a File:
git rm --cached nibba.txt
Check Repository Status: This shows only nibbi.txt staged.
Restoring

Re-add File to Staging:
git add nibba.txt
Check Repository Status: This shows both files staged again.
Committing

Commit Changes:
git commit -m "hey there" nibba.txt nibbi.txt
User Setup (Optional)

Set Global User Info:
git config --global user.email "piyushdoifode05@gmail.com"
git config --global user.name "piyushdoifode"
Further Commit (Optional - Doesn't Work)

You can't commit the same changes again without modifications.
Verification & Removal

List Directory Contents:
ls
Check Repository Status:
git status
Remove File from Disk (Use with caution!):
rm -rf nibba.txt
Check Repository Status: This shows the deleted file.
Restore from Staging

Restore File from Staging:
git restore nibba.txt
This restores the file to the working directory but not the disk.

Restore Attempt (Won't Work)

You can't restore an unstaged file using git restore.
Final Verification

List Directory Contents:
ls
The file remains deleted from the disk.
