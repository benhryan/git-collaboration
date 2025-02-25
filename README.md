These are both fast forward merges. Explain?
Both merges in the image are fast-forward merges because develop had no new commits after neat_branch and messy_branch were created. Instead of creating merge commits, Git simply moves develop forward to the latest commit of each branch, keeping the history linear and clean.

In your own words, write down a scenario that will involve a merge conflict between develop and conflict_branch. Add your answer to readme.doc
A merge conflict will happen if both develop and conflict_branch change the same line in a file differently. If develop changes line 5 in README.md to "Welcome to our project!" while conflict_branch changes it to "Hello from the conflict branch!", Git won’t know which to keep and will ask for a manual fix during the merge.
