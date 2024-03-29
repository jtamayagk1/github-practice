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
![Link an image.](/path/to/image)
![Link to site](/path/to/site)

Lists
Ordered lists start with 1.
unordered lists start with - 

1. Step 1
  - Step 1.1
1. step 2
1. step 3

- a
  - a.a
- b
- c

Tables 
Header1 | Header2 | Header3
-|-|-
a1|a2|a3
b1|b2

Quote text
> This is a quote.

Fill in the gaps with<br> html
<h1>Hello World</h1>
<p>markdown</p>

Working with `code`
```markdown
var a = b
```

Task list
- [x] task 1
- [ ] task 2
- [x] task 3

Slash commands

/code 

- insert a code block you pick the language

/details

- inserts a collapsable detail area you pick the title and content

/saved-replies

- inserts a saved reply

/table

/tasklist

/template
