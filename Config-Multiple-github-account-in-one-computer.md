# *Multiple Git & Github Connection from Single Computer*

### *Step-1* (Add Remote Origin)
```bash
Syntax:
git remote add origin https://github.com/user-name/repo-name.git

Ex:
git remote add origin https://github.com/chaman/test.git
```
### *Step-2* (Set-Url)
### IMP Note: ***This step is vary on different github account***

```
// this is default/primary account
git remote set-url origin git@host-name:user-name/test.git

git remote set-url origin git@github.com:chaman/test.git

// additional/secondary account
git remote set-url origin git@second-host-name:user-name/test.git

git remote set-url origin git@github-second:chagan/repo-name.git

// additional/secondary account
git remote set-url origin git@third-host-name:user-name/test.git

git remote set-url origin git@github-magan:magan/repo-name.git
```
### *Step-3* (Set Branch)
```bash
git branch -M main
```
### *Step-4* (Finally Push on Specific Branch)
```bash
git push -u origin main
```
-------------------------------------------------------
### ***To push local Repo to remote repo, after adding Remote Origin need to "SET-URL" of repository with the different account***

### For the **first GitHub account(Default Account)**
```bash
git remote set-url origin git@github.com:chaman/chaman-tesing.git
```

### For the **second GitHub account**
```bash
git remote set-url origin git@github-second:chagan/power-of-coding.git
```

### For the **third GitHub account**
```bash
git remote set-url origin git@github-magan:magan/power-code.git
```

--------------------------------------------------------------------
### **For the Default GitHub account**
```bash
https://github.com/chaman/my-test-repo.git

git remote set-url origin git@default-host-name:user-name/repo-name.git

git remote set-url origin git@github.com:chaman/my-repo-name.git
```
### **For the chagan GitHub account**
```bash
https://github.com/chagan/code-with-chagan.git

git remote set-url origin git@second-host-name:user-name/repo_name.git

git remote set-url origin git@github-second:chagan/code-with-chagan.git
```

### **For the magan GitHub account**
```bash
https://github.com/magan/magan-code.git

git remote set-url origin git@third-host-name:user-name/repo_name.git

git remote set-url origin git@github-magan:magan/magan-code.git
```

----------------------
# in Config File in ".ssh" directory

#### *-->> config file don't have any file extesion it have only file name "config" in the '.ssh' directory*
#### *-->> Above given step is done after placing and mapping the SSH key with different github account and in 'config' file*

### *Default account*
```bash
Host github.com
  HostName github.com
  User git
  IdentityFile ~/.ssh/id_rsa_default
```

### *Second/chagan's account*
```bash
Host github-second
  HostName github.com
  User git
  IdentityFile ~/.ssh/id_rsa_chagan
```

### *Third/magan's account*
```bash
Host github-magan
  HostName github.com
  User git
  IdentityFile ~/.ssh/id_rsa_magan
```

------------------------------------------------------------
### ***Check existing "Origin" or the local repository***
	git remote -v

### ***Remove existing "Origin" form the local repository***
	git remote remove origin
