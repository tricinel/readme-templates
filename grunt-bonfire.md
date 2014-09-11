# Bonfire app with GruntJS

Additional: node, npm, nvm, bower.
More details on the [github repo](https://github.com/ci-bonfire/Bonfire).

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

- gulp
```shell
npm install -g gulp
```

- bower
```shell
npm install -g bower
```

- PHP, MySQL, Apache

## Install

- Clone the repo
```shell
git clone [github-repo] [directory]
```

- Create a MySQL database and import the mysql dump file in `_db/`

### Grunt tasks

* `grunt` or `grunt build` to build an optimized version of your application
* `grunt serve` to launch a browser sync server on your source files
