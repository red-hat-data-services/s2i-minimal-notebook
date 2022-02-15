# Node.js

The version of Node.js installed to build the last iteration of the
package-lock.json file was: v14.18.2.

Use nvm to install:

```shell
$ sudo n 14.18.2
$ hash -r
$ node --version
v14.18.2
```

Also, to ensure that we end up with consistent results across systems:

```shell
pushd jupyter-server-mathjax
rm -rf node_modules package-lock.json
npm install
popd
```
