# Backroads App

[Working Application - Deployed](https://backroads-app.netlify.app/)

- backroads-html - working html/css/javascript project (contains assets)
- final(complete source code) - working react application
  - navigate to the folder
  - run 'npm install'
  - once the dependencies are installed run 'npm start'

#### React Course

[My React Course](https://www.udemy.com/course/react-tutorial-and-projects-course/?referralCode=FEE6A921AF07E2563CEF)

#### Support

Find the Content Useful? [You can always buy me a coffee](https://www.buymeacoffee.com/johnsmilga)

#### Create New React App

- install

```sh
npx create-react-app@latest backroads-app
```

- run dev server

```sh
npm start
```

#### Continuous Deployment

- fix warnings (About Section)

- netlify account
- github account
- basic git commands :

  - remove existing git repo
    - Mac : rm -rf .git
    - Windows : rmdir -Force -Recurse .git
    - Windows : rd /s /q .git
      Windows commands were shared by students and I have not personally tested them.
  - setup new repo
    - git init
      create an empty git repository
    - git add
      adds new or changed files in your working directory
      to the Git staging area
    - git add .
      adds entire project
      apart from files/directories specified in .gitignore
    - git commit -m "first commit"
      A shortcut command that immediately creates a commit
      with a passed commit message.
    - push to github
      git remote add origin git@github.com:your-profile/repo-name.git
      git branch -M main
      git push -u origin main

#### Benefits

- don't need to keep project locally
- automatic builds

#### Warnings "Gotcha"

- Netlify treats warnings as errors

package.json

```json
"scripts": {
    "start": "react-scripts start",
    "build": "CI= react-scripts build",
    "local-build": "react-scripts build",
    "test": "react-scripts test",
    "eject": "react-scripts eject"
  },
```
