**changes not traceable due to multiple .git directories in project folder :-( had serious problems before with this and had to delete .git directories beneath /IKT_assignments_labs**

# 3b

*Deliverables for both exercises
- A short report (PDF or markdown) that includes:
- A descripNon of what you did in each step.
- Git commands used (copy-paste from your terminal).
- Screenshots or code excerpts for conflict resolution and recovery.*

## Exercise 1 Recap Resolve Merge Conflicts
### Part 1: Repository Setup and Basic Workflow
1. Use the repository of homework assignment 3. Change to its working directory.
2. Create a new branch feature-x, make a change to file.txt and commit.
3. Switch back to main, modify the same part of file.txt, and commit.


### Part 2: Merging with Conflicts
1. Merge feature-x into main.
2. Git will produce a merge conflict. Show how you resolved the conflict.
3. Commit the merge resolu9on.
4. Push your changes to the remote repository.





## Exercise 2 Recovery Scenarios
### Scenario A: git checkout
1. Make a wrong change to a file.txt on main and commit it.
2. Use git checkout to restore the file to its last correct state.
3. Show the command you used and the final file content.
### Scenario B: git reset
1. Add and commit a change to file2.txt.
2. Use git reset --soft HEAD~1 to undo the last commit but keep changes.
3. Use git reset --hard HEAD~1 to completely remove the commit and changes.
4. Document your terminal commands and file status before and aJer.
### Scenario C: git revert
1. Add a “bad” commit to main (e.g., deleNng a line by mistake).
2. Use git revert to undo it with a new commit.
3. Show git log before and aJer the revert.
