Git Workflow: A Step-by-Step Guide
1. Preparation
Create a New Directory:
mkdir git-for-devops

List Directory Contents:
ls

2. Navigation
Change Directory:
cd git-for-devops/
3. Verification
List Directory Contents:
ls

Print Working Directory:
pwd

4. Initialization
Initialize Git Repository:
git init

List All Files (Including Hidden):
ls -a

5. Status Check
Check Repository Status:
git status
6. Adding Files
Create New Files:
touch nibba.txt nibbi.txt

List Directory Contents:
ls

Check Repository Status:
git status

7. Staging and Unstaging
Add Files to Staging:
git add nibba.txt nibbi.txt

Check Repository Status:
git status

Unstage a File:
git rm --cached nibba.txt

Check Repository Status:
git status

8. Restoring
Re-add File to Staging:
git add nibba.txt

Check Repository Status:
git status

9. Committing
Commit Changes:
git commit -m "Initial commit" nibba.txt nibbi.txt
10. User Setup (Optional)
Set Global User Information:
git config --global user.email "your_email@example.com"
git config --global user.name "Your Name"
11. Verification and Removal
List Directory Contents:
ls

Check Repository Status:
git status

Remove File from Disk (Use with Caution):
rm -rf nibba.txt

Check Repository Status:
git status

12. Restore from Staging
Restore File from Staging:
git restore nibba.txt

List Directory Contents:
ls

Check Repository Status:
git status

13. Restore Attempt (Won't Work)
Attempt to Restore Unstaged File:
git restore nibba.txt

Check Repository Status:
git status

14. Final Verification
List Directory Contents:
ls
