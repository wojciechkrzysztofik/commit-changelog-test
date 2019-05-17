## Commit Linter & Changelog Generator  
  
#### How to install  
* Copy package.json, commitlint.config.js and .gitignore to your project root directory (.gitignore contains only node_modules directory in this example).
* run `npm install` in console

#### How to use it
* commit changes with message in correct format ([use this convention](https://github.com/conventional-changelog/commitlint))
* run `npm run release:major`, `npm run release:minor` or `npm run release:patch`.
  
Changelog and new tag will be generated automatically. 
  
  
It's configurated on the basis of this article: https://piecioshka.pl/blog/2019/03/23/husky-commitlint-git-changelog.html (created on the basis of an example)
