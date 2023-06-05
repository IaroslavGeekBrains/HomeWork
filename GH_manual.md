# How do deal with a common repository on Git Hub
1. Fork a common repository to your account.
2. Copy the link to the forked reposytory.
3. Create an empty folder for it on your local computer.
4. Open that new folder in VisualStudio code.
5. Open Terminal.
6. Use __git clone__ and the link (http/...).
7. __Important!__ Go to the right folder using __cd name of the folder__.
8. Check the history of changes: __git status__, __git log__.
9. Create a new branch for your commits and go there: __git checkout -b new_branch__.
10. Right your code on your branch, save, add and commit changes.
11. Check __git status__ to make sure changes have been made.
12. Push your commits to the common repository: __git push --set-upstream origin your_branch_name__.
