\### Step 1: Fork and Clone Repository

\* git clone https://github.com

&#x20; \* \*Description:\* Downloads a local copy of your forked project from GitHub.

&#x20; \* \*Tree Change:\* Connects a new local workspace directory to the remote repository.



\### Step 2: Add Text File

\* echo "2026-09-01" > sivadharshini179.txt

\* git add sivadharshini179.txt

\* git commit -m "2026-09-01"

&#x20; \* \*Description:\* Creates a text file with the date, stages it, and commits it.

&#x20; \* \*Tree Change:\* Creates a new commit snapshot (6d6656c) on the main branch.



\### Step 3: Create Branch

\* git branch sivadharshini179

&#x20; \* \*Description:\* Creates a new branch named after the user.

&#x20; \* \*Tree Change:\* Adds a new branch pointer named sivadharshini179 referencing commit 6d6656c.



\### Step 4: Switch Branch and Add Roll Number File

\* git checkout sivadharshini179

\* echo "A brief description about myself goes here." > AM.SC.U4CSE26252.md

\* git add AM.SC.U4CSE26252.md

\* git commit -m "Add roll number markdown file"

&#x20; \* \*Description:\* Moves to the new branch, creates a profile markdown file, and commits it.

&#x20; \* \*Tree Change:\* The HEAD pointer moves to sivadharshini179. A new commit (e79dc5f) is added to this branch.



\### Step 5: Append Commit Hash

\* echo "Commit Hash: 6d6656c" >> AM.SC.U4CSE26252.md

\* git add AM.SC.U4CSE26252.md

\* git commit -m "Add Step 2 commit hash to markdown"

&#x20; \* \*Description:\* Appends the Step 2 hash inside the markdown file and commits it.

&#x20; \* \*Tree Change:\* Adds another commit along the sivadharshini179 branch timeline.



\### Step 6: Merge Branch

\* git checkout main

\* git merge sivadharshini179

&#x20; \* \*Description:\* Returns to the main branch and incorporates the branch changes.

&#x20; \* \*Tree Change:\* The main pointer fast-forwards to catch up with the latest commit on the personal branch.



\### Step 7: Edit README

\* echo "Sivadharshini" >> README.md

\* git add README.md

\* git commit -m "Add my name to the end of README"

&#x20; \* \*Description:\* Appends the user's name to the repository documentation and commits it.

&#x20; \* \*Tree Change:\* Adds a new commit to the updated main branch timeline.



\### Step 8: Git Reset Practice

\* echo "Biryani" >> README.md

\* git add README.md

\* git reset HEAD README.md

\* git restore README.md

&#x20; \* \*Description:\* Adds a favorite dish, stages it, unstages it with reset, and clears the file changes.

&#x20; \* \*Tree Change:\* Modifies the index and working directory, but leaves the commit history tree completely untouched.



