Simulate a merge conflict by starting a feature b one commit before the last commit on main branch. (the last commit on main b has changed the first line of test.ts)

Modify the same line on the feature b.

Merge feature b in main --> conflict.

Git doesn't know what branch to take the change from. (commit made on feature b is not sequential to main b last commit so it can't take precedence, therefore the conflict happens)
