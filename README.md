# steps 
1 :- Basic structure of react-app
2 :- Configure webpack & typescript to allow rendering of images & SVGs
3 :- setup webpack config for multiple env.
4 :- Add React refresh
5 :- Linting with EsLint
6 :- Code Formatting with Prettier
7 :- Husky

# Folder Structure
  1. React-boilerplate/
    |-- build/
    |-- src/
    |    |-- assets/images
    |    |-- index.tsx
    |    |-- Index.tsx
    |    |-- App.tsx
    |    |-- declaration.d.ts
    |
    |-- webpack/
    |-- .babelrc
    |-- tsconfig.js
    |-- .prettierrc.js
    |-- .eslintrc.js
    |-- .gitignore

# initialize - repo 
    cmd :- `git init`

# initialize a project
    cmd :- `npm init -y`

# create a entry file in the src/index.html
    src/
     |-- index.html
     |-- Index.tsx
     |-- App.tsx
     |-- declaration.d.ts
     |-- style.css

# add html boiler plate in it.
# add `<div id="root"></div>` code in the body.

# add ignored files in the .gitignore file
    1. build
    2. node_modules

# install Dependencies Packages `npm i package-name`
    1. react 
    2. react-dom

# add react-code in the files
    1. index.html
    2. Index.tsx
    3. App.tsx

# install Dev-Dependencies Packages `npm i -D package-name` for typescript [PACKAGES]
    1. typescript
    2. @types/react
    3. @types/react-dom

# add config file for typescript file
    1. tsconfig.json file in the root directory
    2. add configuration in the tsconfig.json file.

# install Dev-Dependencies Packages `npm i -D package-name` for Babel for compiling ts to js [PACKAGES]
    1. @babel/core
    2. @babel/preset-env
    3. @babel/preset-react
    4. @babel/preset-typescript
    5. @babel/plugin-transform-runtime

# add babel configuration in the project
    1. create .babelrc file in the root directory
    2. add babel configurations in the file

# install Dev-Dependencies Packages `npm i -D package-name` for webpack for compiling [PACKAGES]
    1. webpack
    2. webpack-cli
    3. webpack-dev-server
    4. html-webpack-plugin

# install Dev-Dependencies Packages `npm i -D package-name` for babel transpiled [PACKAGES]
    1. babel-loader

# create webpack-files in the webpack folder
    1. webpack.config.js
    2. webpack.common.js
    3. webpack.dev.js
    4. webpack.prod.js

# install Dev-Dependencies Packages `npm i -D package-name` for webpack merging [PACKAGES]
    1. webpack-merge

# add configuration in the webpack.config.js file
# add env. specific configurations other files
# merge all common & env. specific configuration of webpack 

# add start cmd in the package.json file to compile the project & open up in the browser

# add style.css files for the project
# install Dev-Dependencies Packages `npm i -D package-name` for style-loaders [PACKAGES]
    1. css-loader
    2. style-loader
# add rules in the webpack-config files for images/styles/etc. {in webpack 5 - its inbuilt support for images/svgs, for previous versions have to add:- asset/inline package for svg}
# create the declaration.d.ts file in the `src/declaration.d.ts` 

# add webpack cmds for start/build in the package.json file

# install Dev-Dependencies Packages `npm i -D package-name` for react-refresh saves app state [PACKAGES]
    1. @pmmmwh/react-refresh-webpack-plugin 
    2. react-refresh
# add react-refresh plugin in the webpack.dev.js file.

# install Dev-Dependencies Packages `npm i -D package-name` for EsLint [PACKAGES]
    1. eslint
    2. eslint-plugin-react
    3. eslint-plugin-react-hooks
    4. @typescript-eslint/parser
    5. @typescript-eslint/eslint-plugin
    6. eslint-plugin-import
    7. eslint-plugin-jsx-a11y

# add eslint file in the root folder `.eslintrc.js`
# add extends & rules in the .eslintrc.js file

# install Dev-Dependencies Packages `npm i -D package-name` for Prettier [PACKAGES]
    1. prettier
    2. eslint-config-prettier
    3. eslint-plugin-prettier

# add prettier configuration file in the root directory `.prettierrc.js`
# add prettier configuration to the file

# install Dev-Dependencies Packages `npm i -D package-name` for Husky to format code before committing [PACKAGES]
    1. lint-staged
    2. husky@4
# add husky & list-staged configuration in the package.json file


# install Dev-Dependencies Packages `npm i -D package-name` for babel [PACKAGES]
    1. @babel/runtime
    2. @babel/plugin-transform-runtime
# update these plugins in the .babelrc.js file

# install Dev-Dependencies Packages `npm i -D package-name` for webpack - copy files/assets to build folder [PACKAGES]
    1. copy-webpack-plugin
# 
