Simulate a merge conflict by starting a feature b one commit before the last commit on main branch. (the last commit has changed a line)
Modify the same line on the feature b branch.
Merge feature b in main --> conflict.
Git doesn't know what branch to take the change from. (commits are not sequential)
