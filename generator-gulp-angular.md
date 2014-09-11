# Yeoman generator for AngularJS with GulpJS

Additional: node, npm, nvm, bower.
More details on the [github repo](https://github.com/Swiip/generator-gulp-angular).

## Requirements

- node & npm
```
Install from http://nodejs.org/
```

- nvm
```shell
curl https://raw.githubusercontent.com/creationix/nvm/v0.16.0/install.sh | bash
```

- Install the version of node you need by
```shell
nvm install 0.10.30 && nvm use 0.10.30
```

- yeoman
```shell
npm install -g yo
```

- gulp
```shell
npm install -g gulp
```

- bower
```shell
npm install -g bower
```

## Install

- Install the generator
```shell
npm install -g generator-gulp-angular
```

## Usage

- Create a new directory and cd into it
```shell
mkdir my-new-project && cd $_
```

- Run the generator
```shell
yo gulp-angular [app-name]
```

### Gulp tasks

* `gulp` or `gulp build` to build an optimized version of your application in `/dist`
* `gulp serve` to launch a browser sync server on your source files
* `gulp serve:dist` to launch a server on your optimized application
* `gulp wiredep` to fill bower dependencies in your `.html` file(s)
* `gulp test` to launch your unit tests with Karma
* `gulp protractor` to launch your e2e tests with Protractor
* `gulp protractor:dist` to launch your e2e tests with Protractor on the dist files
