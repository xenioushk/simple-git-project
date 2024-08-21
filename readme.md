# A simple-git-project

### Step 1

Create a project on local machine and initalize git repository.

```bash
git init
```

### Step 2

Create repository both Github and Gitlab.

### Step 3

Add both GitHub and Gitlab remote repository.

```bash
git remote add github https://github.com/your-username/your-repo.git
```

```bash
git remote add gitlab https://gitlab.com/your-username/your-repo.git
```

### Step 4

Verify the Remotes

```bash
git remote -v
```

### Step 5

Push all the changes to both repsoitory.

```bash
git push github main
git push gitlab main
```

OR, use the shorthand command.

```bash
git push --all
```

### Step 6

For pushing **all branch**, you can use the following commands.

```bash
git push github --all
git push gitlab --all
```

For pushing a **specific branch**, you can use the following commands.

```bash
git push github <BRANCH_NAME>
git push gitlab <BRANCH_NAME>
```
