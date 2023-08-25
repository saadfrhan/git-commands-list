# Git Commands List

 <details>
    <summary>Table of Contents
</summary>
		<p>

- [Basic Workflow](#basic-workflow)
	- [Initialize a git repository](#initialize-a-git-repository)
	- [Check the status of the repository](#check-the-status-of-the-repository)
	- [Add files to the staging area](#add-files-to-the-staging-area)
	- [Unstage files from the staging area](#unstage-files-from-the-staging-area)
	- [Discard changes of the last commit](#discard-changes-of-the-last-commit)
	- [Commit changes to the repository](#commit-changes-to-the-repository)
	- [Check the log of commits](#check-the-log-of-commits)
	- [.gitignore](#gitignore)

		</p>
		</details>

## Basic Workflow

### Initialize a git repository

```bash
git init
```

### Check the status of the repository

```bash
git status
```

### Add files to the staging area

```bash
git add <filenames-with-spaces>
# OR
git add .
```

### Unstage files from the staging area

```bash
git reset <filenames-with-spaces>
# OR
git reset 
```

### Discard changes of the last commit

```bash
git reset --hard
```

### Commit changes to the repository

```bash
git commit -m "commit message"
# use -am to add and commit in one step
```

### Check the log of commits

```bash
git log
```

### .gitignore

```bash
# path to a specific file
path/to/file.txt
# files with same name
file.txt
# files with a specific extension
*.txt
# all files of a specific folder in a specific path
path/to/folder/*
# folder in the root of the repository
/folder
```