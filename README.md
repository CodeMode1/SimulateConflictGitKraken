Simulate a merge conflict by starting a feature b one commit before the last commit on main branch. 
(the first line of test.ts is changed on the last commit of main b)

Modify the same line on the feature b.

Merge feature b in main --> conflict.

Git doesn't know what branch to take the change from. 
(commit on feature b is not made directly after main b last commit so it can't take precedence and apply its changes, therefore the conflict happens)
