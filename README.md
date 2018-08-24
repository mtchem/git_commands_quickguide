# Git Commands Quickguide
<p>
	<H3> A short description of the git commands I use the most </H3>
</p>

<li><b>git init</b> : initialize a git repository</li>
<li><b>git clone *github URL* </b>: downloads the github repo from the github URL </li>
<li><b>git status </b>: shows branch name and status of files</li>
<li><b>git add *filename*</b>: moves 'filename' to staging area (and starts the tracking process) </li>
<li><b>git commit -a -m 'message'</b>: commits all of the files you are currently tracking with the message</li>
<li><b>git checkout -b *branch name* </b>: makes a branch and then checks it out</li>
<li><b>git push origin master</b>: pushes all of your local commits to the origin (probably the github you cloned from)</li>

<p>
	<H3> A short description of the git commands I use to explore commits</H3>
</p>

<li><b>git log --stat</b>: shows affected files, additions, and subtractions</li>
<li><b>git diff *fileID1* *fileID2*</b>: compaires fileID1 and fileID2</li>
<li><b>git diff</b>: compairs staging area to most recent commit</li>
<li><b>git diff --staged</b>: compairs staging area to most recent commit</li>
<li><b>git log --graph --online *branch1* *branch2*</b>: visualizes the commits of branch1 and branch2</li>
<li><b>git show *commit ID*</b>: shows difference between the commit ID and it's parent</li>

<p>
	<H3> Other git commands that might be useful</H3>
</p>

<li><b>git remote -v </b>: returns remote URL info</li>
<li><b>git add -i </b>: opens menu to group add untracked files</li>
<li><b>git fetch origin</b>: update local with github master</li>
<li><b>git branch -d *branch name*</b>: deletes branch name</li>
<li><b>git remote</b>: returns list of remotes</li>
<li><b>git remote add *remote name* *URL of remote*</b>: creates a remote for the file</li>
<li><b>git checkout *commit ID*</b>: checks out the commit ID</li>
<li><b>git merge *branch*</b>: merges branch into current directory</li>
<li><b>git merge --abort</b>: aborts merge</li>
<li><b>git reset --hard</b>: reverts to last commit and DELETES any uncommited changes</li>