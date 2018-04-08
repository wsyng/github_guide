# Github Guide

create repo on github</br>
git init [project]

cd [project]

vim README.md</br>
	Big Title</br>
	This is a git repo

vim sample.py

git add README.md</br>
git add sample.py

git commit -m "test git repo"

# If this is a new repo
git remote add origin [url]

	Enter credentials

# Otherwise
git push origin [branch]

----------------------------------------------------------

# Remove file:</br>
git rm file1.txt</br>
git commit -m "remove file1.txt"

# Remove file from repo only (not local file system):</br>
git rm --cached file1.txt</br>
git commit -m "remove file1.txt"</br>
git push origin [branch]
