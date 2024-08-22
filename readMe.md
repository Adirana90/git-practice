# Documentation for git

- Initializa the project

This should be done at the begining of the project only.

```bash
git init
```

-check the user name and email
if user name and email is not set, set them.

```bash
git config user.name "<github user name>"
git config user.email "<github email>"
```

-check the status of the project
This is the most used command.

```bash
git status
```

-adding files to staging area

```bash
git add <file_or_folder_path>
```

-commit the change file

```bash
git commit -m "<your message>"
```

-Amend the last commit message

```bash
git commit --amend
```

- message should me in present tense. e.g. setup the initial git

```bash
git log --oneline
```

- Adding remote to our repository

```bash
git remote add orgin <repository_url>
```

- Check current branch

```bash
git branch
```

-rename current branch

```bash
git branch -M <>
```

- push letest changes to the remote

```bash
git push origin <branch_name>
```

- checkout new branch

```bash
git checkout -b <branch_name>
```

-checkout existing branch

```bash
git checkout <branch_name>
```

- pull latest code from remote

```bash
git pull origin <branch_name>
```
