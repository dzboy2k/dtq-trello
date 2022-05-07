## Trello

### 01 - Tạo project
```
node 14.7.0
npm 6.14.7
yarn 1.19.1
cmd
  ls -l (ls)
  npx create-react-app trello-trungquandev-web
  npm start
  yarn start
  clear
delete 
  App.test.js
  index.css
  logo.svg
  setupTests.js
cmd
  git init
  git status
  git remote -v
github
  Description: Awesome Course - https://trungquandev.com
cmd
  git remote add origin (repository)
  git remote -v
  git add .
  git push origin main
```

### 02 - Design & Code giao diện
#### 02 - P1 - Update Readme
```
cmd
  git branch
  git checkout -b update_readme
markdown syntax github => Mastering Markdown · GitHub Guides

vscode
  atom on dark => Atom On Dark Theme
  vscode icons
cmd
  git status
  git add .
  git commit -m "Update readme."
  git push origin update_readme
github
  main => Compare & pull request
    base: main
    compara: update_readme
  => Create pull request
  Files changed
  Review changes
cmd
  Thay đổi file readme
  git add .
  git commit --amend
  :wq
  git push origin update_readme -f
github
  Conversation => Merge pull request => Confirm merge
  Delete branch
cmd
  git checkout main
  git pull origin main
  clear
  git branch
  git branch -D update_readme
  git checkout -b design_trello
  clear
  yarn start
```

#### 02 - P2 - Design Trello
```
cmd 
  nvm use 14.7.0
  npm i node-sass --save
import google font css
webkit-scrollbar
cmd 
  git status
  git add .
  git commit -m "Design trello Front-end."
  git push origin design_trello
Compare & pull request => Create pull request => Merge pull request
cmd
  git checkout main
  git pull origin main
  git branch
  git branch -D design_trello
  git status
```

### 03 - Tái cấu trúc
```
cmd
  git checkout -b clean_architecture
  clear
  yarn start
facebook/create-react-app -> Issues
  https://github.com/facebook/create-react-app/issues/87
jsconfig.json => jsconfig.json Reference - Visual Studio Code
Ctrl + P
Ctrl + Shift + F
cmd
  git status
  git add .
  git commit -m "03-Clean React Architecture." 
  git push origin clean_architecture
github
  Compare & pull request => Create pull request
  Files changed
  Merge pull request => Confirm merge
cmd
  git checkout main
  git pull origin main
  clear
  git branch -D clean_architecture
  git branch
```

### 04 - Khởi tạo dữ liệu mẫu
```
cmd
  git checkout -b initial_sample_data
  clear
lodash npm
  npm i lodash --save
  npm audit fix
sort javascript
cmd 
  git status
  git add .
  git commit -m "04-Initial sample data."
  git push origin initial_sample_data
github
  Compare & pull request => Create pull request
  Files changed
  Merge pull request => Confirm merge
cmd 
  git checkout main
  git pull origin main
  git branch
  git branch -D initial_sample_data
  clear
```