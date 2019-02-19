# Clean project with parcel, es6 and sass
![MIT License](https://img.shields.io/github/license/TwiztedDesign/vff.svg)


# Usage
Create a new empty repo on GitHub 
    
    git clone hhttps://github.com/TwiztedDesign/clean-parcel-project.git [my-project-name]
    cd [my-project-name] 
   
Clean the README

    rm README.md && touch README.md
    
If you have LICENSE, you can clean it too.

    rm LICENSE
    touch LICENSE
    
Remove all git info from the boilerplate

    rm -rf .git
    
Initiate the new git repo

    git init
    git add -A
    git commit -m "first commit"
    git remote add origin [my-project remote repo]
    git push -u origin master
    
Install Dependencies

    npm install

## Build
    npm run build
    
This will generate the file /dist/index.js.  

## Development
    npm run watch
## Publish
    npm publish

## Tests
    npm test


## 🍻 Cheers 🍻 
