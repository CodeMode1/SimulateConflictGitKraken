Simulate a merge conflict by starting a feature b before the last commit on main b:

* Modify the first line of test.ts on main b and commit.

* Checkout the commit before this commit on main b.

* Start a new feature b from there.

* Modify the same line on the feature b and commit.

* Merge feature b in main --> conflict.

Git doesn't know what b to take the change from. 
(commit on feature b is not made after main b last commit so it can't take precedence and apply its changes, therefore the conflict happens)
