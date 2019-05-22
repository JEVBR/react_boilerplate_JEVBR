Create new projet from this boilerplate:

goto folder wher you want the new project
git clone git@github.com: thisname new_project_name
cd ew_project_name
yarn install
rm -rf .git
git init
hub create JEVBR/react_boilerplate_JEVBR
git add .
git commit -m "first commit"
yarn start


# react-boilerplate

Simple react starter with the following config:

- React, ReactDOM
- Webpack 4
- Babel with es2015 and react presets
- Bootstrap (css only, loaded from a cdn in `index.html`)
- work with `.js` or `.jsx` files
- main `application.scss` stylesheet is imported in `index.js` as a module to enjoy hot reloading

## Scripts

To start the local Webpack Dev Server (usually on port `8080`):

```bash
yarn start
```

To lint all JavaScript files in the `src` folder:

```bash
yarn lint
```

To build and deploy your app to `gh-pages` branch on the GitHub repo:

```bash
yarn deploy
```
