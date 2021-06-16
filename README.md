# create a new git repo on github.com
owner: hyluo2017
repo name: n2tnotes
(not initialize repo with a README)

# project setup
create a dist folder to house all files to be pushed to github
$ npm init -y (create package.json)
$ npm i gh-pages (install gh-pages - a node module, this will create node_modeules folder)
in package.json, add:
    "homepage": "https://hyluo2017.github.io/n2tnotes",
    in "scripts" add: "deploy": "gh-pages -d dist"
create .gitignore file

# git local
$ git init (create a .git folder)
$ git add . (add everything to staging)

