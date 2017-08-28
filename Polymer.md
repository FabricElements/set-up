# Set up new project on Polymer
Base configuration files for a polymer project

## How to use
1. Clone this repository locally
2. Copy all the contents from the directory `base` to the root
directory of your new Polymer Project.
```shell
$ cp set-up/polymer/** /path-to-your-new-project/
$ cp set-up/polymer/.* /path-to-your-new-project/
```
3. Go to your project root directory and init polymer
```shell
$ polymer init
```
3. Open `bower.json` and copy the `name` of the project
and paste it in `package.json`.
4. Install and update node dependencies
```shell
$ npm install
$ npm update
```
Or if you use yarn
```shell
$ yarn install
$ yarn upgrade
```
3. Run polymer
```shell
$ polymer serve
```