# Complete Walk-Thru-Guide to set up a new repository

## Create repository online and clone it to local

1. Go to github.com and create new repository (repo)
2. Copy SSH link
3. Open Terminal
4. Navigate into neuefische folder
5. Clone Repo
   `git clone [link from github]`
6. Ignore warning that repo appears empty

## Fill repo with essentials

### Methode A - with terminal

Add folder structure with
`mkdir [foldername]`

```
mkdir src
(cd) src
mkdir scss
mkdir components
mkdir pages
(cd) scss
mkdir partials
```

Add files with
`touch [filename.extension]`

in root dir [= name of your repo]

```
touch .gitignore
touch README.md
touch .posthtmlrc
```

in src dir

```
touch index.html
```

in scss dir

```
touch style.scss
```

in scss/partials

```
touch \_global.scss
touch \_variables.scss
```

(order of creation doesn't matter)

### Methode B - with VSCode

1. load repo into VSCode by typing
   `code .` while inside the newly created folder called [name of your repo]
2. create folder structure described about by clicking the "new folder"-icon next to the name of the repo [might be hidden by it, hover over it]
3. then create the files described above with the "new file"-icon next to the "new folder"-icon

## Initiating repo and installing JS-Packages

IF still in terminal: Switch to VSCode with `code .` while inside the root folder of you repo [name of your repo]

1. See and check result and give yourself a tap on the back

- open terminal in VSCode ( CONTROL + ` )

2. Use `npm init` to initalize repo and add info OR skip through automatically with `npm init -y`
3. Install parcel-bundler, sass and posthtml 'at once' inside the repo with
   `npm i -D parcel-bundler sass posthtml-include`
4. Click "Refresh Explorer" in VSCode to see new files & folders
5. Open .gitignore and add

```
.DS-Store
.Cache
dist
node_modules
```

6. Open package.json and add to "scripts" (you can replace the "test")

```
"dev": "parcel src/_.html",
"build": "parcel build src/_.html"
```

## Configure the basics

1. Got to index.html and add base html text with Emmit and ! + TAB
2. Bind style.scss into index.html by adding
   `<link rel="stylesheet" href="scss/style.scss" />` to the head

-- Add content like "YEAH, I did IT" to e.g. the body--

3. Go to \_global.scss and add:

```
*,
*::before,
*::after {
  box-sizing: border-box;
}
```

4. Go to style.scss and add:

```
@import "partials/variables";
@import "partials/global";
```

5. Save changes with COMMAND + S

## Test your setup

1. Run script with `npm run dev`
2. Click on URL (e.g. http://localhost:1234) to see a preview of your work so far
3. CONTROL + C to get back to normal terminal

## Initial commit

Go to root dir of new repo

1. `git status` to see all you've accomplished
2. `git add .` to add all files and changes
3. `git commit -m "initial commit"` to make the initial commit
4. `git status` if you want to be sure
5. `git push` to finally upload your changes to github
6. another `git status` to see everything is fine should say:

```
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean
```

7. ENJOY your moment and then GET CREATIVE - **happy coding!**
