git --version

# Setting username and password
git config --global user.name <username>
git config --global user.email <email>

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

Creating a _italic_ text *italic*
Create a __bold__ text **bold**

**bold and _Italic_**
_italic and **bold**_

Use esvape char \ to actually see _ or *
\_For \*\*Example\*\*\_

# h1
## h2
### h3
#### h4
##### h5
###### h6

Link to Images
![Link an image.](https://www.google.com/aclk?sa=l&ai=DChcSEwiek8f_ssqEAxWbSEcBHQh8CEgYABABGgJxdQ&ase=2&gclid=CjwKCAiAivGuBhBEEiwAWiFmYYrpDPIUarclDK46dWT41hgRqrndoLQXNvtbrUV9wUaAG_NKr1T3eRoCSdIQAvD_BwE&sig=AOD64_2KeX4GeF-KAdISO5cD32GvPIproA&ctype=5&nis=6&adurl&ved=2ahUKEwjuorr_ssqEAxUPrIkEHVhjCkEQvhd6BAgBEHs)
