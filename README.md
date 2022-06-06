# bibumbap

## Table of Contents
1. [Introduction](#bumpa-css--bibumbap)
2. [Getting Started](#getting-started)
3. [Future Development](#future-development)

## Bumpa css / Bibumbap

Bumpa css framework build using sass, and for now developed only for Bumpa internal projects. build by Bumpa Tech.

buat yang mau nambahin file atau edit styling dipersilahkan ya, tapi kalo bisa tetap mengikuti struktur yang telah ada

```
// folder structure plan
- dist/
  - bibumbap.css
  - bibumbap.min.css
- src/
  - index.scss
  - components/
    - _button.scss
    - _card.scss
    - _example.scss
  - variables.scss
  - helpers.scss
- demo // for development only
  - index.html
  - components/
    - button.html
    - card.html
    - etc.
```

all components, variable, and helpers will be improted to the index file, then the index file will be builded into the bibumbap.css on the dist file.

please also be aware of our package.json file. it already contain save dependencies sass package, and modified script to run.
`npm run build` -> you can run this every time you want to build current scss file into dist/bibumbap.css
`npm run watch` -> you can run this to watch your changes, and automatically update the dis/bibumbap.css file

<br>

## Getting Started
### Install Dependencies
```bash
npm install
```

### Build SASS File
```bash
npm run build
```

### Watch SASS File
```bash
npm run watch
```


<br>

## Future Development
- we will add 
  - git commit hook, so everytime we commit, it will auto running `npm run build` command
  - proper documentation


<br>

## Related Documentation
[Sass](https://sass-lang.com/install)
