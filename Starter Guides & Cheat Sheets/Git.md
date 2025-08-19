

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


**The Guide**

**What is Git?**
Git (Not to be confused with GitHub) is a Version Control Tool. It is used to track and manage files, but also can be used for text in the instance of this Obsidian Vault. Using Git I can pull, add, commit and push changes I made here which I can then manage and rollback to if needed.

**So what is GitHub?**
GitHub as the name suggest, is a Hub for people using Git (Shocking isn't it). More specifically it is used to share git repos online. You use your Git Commands to update your repo here and can also pull the latest changes made to it to your system. One thing to keep in mind is that with Git you are working on your OWN machine, but when you push it to Github any changes you made will be sent to that public repository on the website, so be sure NOT to put anything important like passwords, API keys and other sensitive data.


**Getting Started: Installing Git**
You can install Git from their website: 

https://git-scm.com/downloads

Install the one relevant to your system and follow through the Installer Wizard. You can keep the settings to default. 

Next right click in a folder, empty desktop or anywhere that you can get your Context Menu and click "Open Git Bash." From there type into the new CMD/Terminal Window:

```git
git --version
```

**Getting Started: Setting Up Git**

