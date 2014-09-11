# Yeoman generator for AngularJS with GruntJS

Additional: node, npm, nvm, bower.
More details on the [github repo](https://github.com/yeoman/generator-angular).

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
npm install -g generator-angular
```

## Usage

- Create a new directory and cd into it
```shell
mkdir my-new-project && cd $_
```

- Run the generator
```shell
yo angular [app-name]
```

### Grunt tasks

* `grunt` or `grunt build` to build an optimized version of your application in `/dist`
* `grunt serve` to launch a browser server on your source files
* `grunt test` to launch your unit tests with Karma
