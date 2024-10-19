1. Create a new directory:

mkdir git-for-devops
2. List the contents of the current directory:

ls
3. Change to the newly created directory:

cd git-for-devops/
4. List the contents of the current directory:

ls
5. Print the current working directory:

pwd
6. Initialize a Git repository:

git init
7. List the contents of the current directory:

ls
8. List all files, including hidden ones:

ls -a
9. Check the current status of the repository:

git status
10. Create two new files:

touch nibba.txt nibbi.txt
11. List the contents of the current directory:

ls
12. Check the current status of the repository:

git status
13. Add the new files to the staging area:

git add nibba.txt nibbi.txt
14. Check the current status of the repository:

git status
15. Remove the "nibba.txt" file from the staging area:

git rm --cached nibba.txt
16. Check the current status of the repository:

git status
17. Add the "nibba.txt" file back to the staging area:

git add nibba.txt
18. Check the current status of the repository:

git status
19. Commit the changes to the repository:

git commit -m "hey there" nibba.txt nibbi.txt
20. Set your global Git user information:

git config --global user.email "piyushdoifode05@gmail.com"
git config --global user.name "piyushdoifode"
21. Commit the changes to the repository again:

git commit -m "hey there" nibba.txt nibbi.txt
22. List the contents of the current directory:

ls
23. Check the current status of the repository:

git status
24. Remove the "nibba.txt" file from the disk:

rm -rf nibba.txt
25. Check the current status of the repository:

git status
26. Restore the "nibba.txt" file from the staging area:

git restore nibba.txt
27. List the contents of the current directory:

ls
28. Check the current status of the repository:

git status
29. Attempt to restore the "nibba.txt" file again (won't work):

git restore nibba.txt
30. Check the current status of the repository:

git status
31. List the contents of the current directory:

ls













