# Github Guide

create repo on github

git init [project]
cd [project]

vim README.md
	Big Title
	This is a git repo

vim sample.py

git add README.md
git add sample.py

git commit -m "test git repo"

# If this is a new repo
git remote add origin [url]

	Enter credentials

# Otherwise
git push origin [branch]

----------------------------------------------------------

Remove file:
git rm file1.txt
git commit -m "remove file1.txt"

Remove file from repo only (not local file system):
git rm --cached file1.txt
git commit -m "remove file1.txt"

git push origin [branch]
