<h1>Git and GitHub Basics</h1>

<h2>This README covers the main Git and GitHub concepts I've learned.</h2>

<h3>Creating a Repository</h3>
<ul>
  <li>On GitHub: Click the '+' icon, choose "New repository"</li>
  <li>Locally: Use `git init` in a folder</li>
</ul>

<h3>Cloning a Repository</h3>
<ul>
  <li>Use `git clone <repository-url>`</li>
</ul>

<h3>Creating Branches</h3>
<ul>
  <li>`git branch <branch-name>` to create</li>
  <li>`git checkout -b <branch-name>` to create and switch</li>
</ul>

<h3>Committing Changes</h3>
<ol>
  <li>`git add <file>` or `git add .`</li>
  <li>`git commit -m "Message"`</li>
</ol>

<h3>Reverting Commits</h3>
<ul>
  <li>`git revert <commit-hash>`</li>
</ul>

<h3>Pulling and Pushing Changes</h3>
<ul>
  <li>Pull: `git pull origin <branch>`</li>
    <li>Push: `git push origin <branch>`</li>
</ul>

<h3>Fetching Changes</h3>
<ul>
  <li>`git fetch origin`</li>
</ul>

<h3>Merging Branches</h3>
<ol>
  <li>`git checkout <target-branch>`</li>
    <li>`git merge <source-branch>`</li>
</ol>

<h3>Renaming Branches</h3>
<ul>
  <li>`git branch -m <old-name> <new-name>`</li>
</ul>

<h3>Pull Requests</h3>
<ul>
  <li>Create on GitHub after pushing a branch</li>
  <li>Review, comment, and merge on GitHub</li>
</ul>

<h3>Reverting Pull Requests</h3>
<ul>
  <li>Use the "Revert" button on GitHub</li>
</ul>
