# babel-webpack-starter

This project is a starter template for [webpack](https://webpack.github.io/) and [Babel](https://babeljs.io/) projects.


## Usage

### Installation

    # clone the repository and only keep the last commit's history
    git clone --depth 1 https://github.com/willshiao/babel-webpack-starter.git
    
    cd babel-webpack-starter
    
    # install dependencies
    npm install
    
    # build using webpack to ensure everything is working
    npm run build

### Scripts

`npm run build` generates a build (without source maps) in the `dist` directory. Cleans the `dist` directory before building.

`npm run build-dev` generates a build with source maps in the `dist` directory.

`npm run clean` removes the `dist` directory.

`npm run dev` starts the development webserver.
