# Undoing Changes 

1) Staged changes ---> Changes are added but not still commited<br>
    git reset file_name ---> resets specifeied file changes<br>
    git reset ---> resets all changed files <br>

2) Changes are commited (for single commit)<br>
    git reset HEAD~1 ---> latest commit will be resetted<br>

3) Changes are commited (for many commits)<br>
    git reset commit_hash ---> hash can be observed by using git log command<br>
    git reset --hard commit_hash ---> when using hard the changes made on vs code will also be altered and now we will not see the file as modified <br>