git --version

# Setting username and password
git config --global user.name <username>
git config --global user.email <email>

### TEST TEST TEST

# See config
git config --list

# Creating a repo
```s
mkdir Notes
cd Notes
git init --initial-branch=main || git init -b main
or
git init
git checkout -b main
```

# check status
```s
git status
```

# Show content of working tree
```s
ls 
la -a #Will also show hiddend '.' folders
```

# stage changes
git add

# commit changes
git commit
includes:
- author's name and e-mail address
- the date 
- comments about what you did (and why) 
- an optional digital signature
- ahe unique identifier of the preceding commit.

# See info about previous commits
git log
