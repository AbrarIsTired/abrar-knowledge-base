**GIT Cheat Sheet**
Account Setup (New Device)
```
git config --global user.name "USERNAME"
git config --global user.email "EMAIL"
```

Setting Up Repo (Locally/New Device):
```
git clone REPO_LINK
```

Pull Changes (Repo -> Local):
```
git pull
```

Force Pull from Main (Repo -> Local):
```
git fetch origin
git reset --hard origin/main
```

Staging Changes (Edited, Altered or Deleted Files):
```
git add .
```

Commit Changes w/ Note:
```
git commit -m "Message"
```

Push Changes to Repo (Local -> Repo):
```
git push origin main

OR

git push
```

Create & Move to Branch
```
git checkout -b branchName
```
