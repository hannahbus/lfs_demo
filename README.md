# git lfs

Repository to test git lfs and manage GitHub repositories with large datasets.

Instruction for Mac Users 

If not installed, install Homebrew, a package manager for Mac and Linux users by executing

```/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"```

Then, install git lfs (lfs is an acronym for large file storage) 

```brew install git-lfs```

Set up git lfs for your user account by 

```git lfs install```

Needs to be done only once per account. 

Then specify, which file types should tracked via git lfs, here e.g. 

```git lfs track "*.csv"```

Update git attributes by typing in 

```git add .gitattributes```

Usual procedure 

```git add * 
git commit -m "foo" 
git push```
