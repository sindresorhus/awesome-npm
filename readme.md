# awesome npm [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [<img src="https://github.com/npm/logos/blob/7fb0bc425e0dac1bab065217c4ed595594448db4/npm-transparent.png" width="200" align="right" alt="npm">](https://www.npmjs.com)

> Awesome [npm](https://www.npmjs.com) resources and tips

You might also like [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs).

*Please read the [contribution guidelines](contributing.md) before contributing.*


## Table of Contents

- [Articles](#articles)
- [Tools](#tools)
- [Packages](#packages)
- [Clients](#clients)
- [Tips](#tips)
- [FAQ](#faq)
- [Community](#community)
- [Documentation](#documentation)
- [Support](#support)


## Articles

- [Small focused modules](https://github.com/sindresorhus/ama/issues/10#issuecomment-117766328)
- [Unix philosophy and Node.js](http://blog.izs.me/post/48281998870/unix-philosophy-and-nodejs) - Write programs that do one thing and do it well.
- [Writing small modules](http://substack.net/how_I_write_modules)
- [Semver: A Primer](https://nodesource.com/blog/semver-a-primer/) *(Must read!)*
- [Semver: Tilde and Caret](https://nodesource.com/blog/semver-tilde-and-caret/)
- [Offline installation of npm packages](https://addyosmani.com/blog/using-npm-offline/)
- [Task automation with npm run](http://substack.net/task_automation_with_npm_run)
- [How to use npm as a build tool](http://blog.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool/)
- [Install npm packages globally without sudo on OS X and Linux](https://github.com/sindresorhus/guides/blob/master/npm-global-without-sudo.md)
- [Optimizing the footprint of an npm package](https://medium.com/@goldglovecb/npm-needs-a-personal-trainer-537e0f8859c6)
- [The Art of Node](https://github.com/maxogden/art-of-node#modules) - An introduction to Node.js and client-side development with npm.


## Tools

### Web

- [npmsearch](http://npmsearch.com) - Fast package search with ranking based on metrics like stars, dependents, release frequency, etc.
- [node-modules](http://node-modules.com) - Personalized package search based on your GitHub social graph.
- [NodeICO](https://nodei.co/) - Package badges.
- [Libraries.io](https://libraries.io/npm) - Package discovery.
- [npm-stat](http://npm-stat.com) - Statistics charts for packages.
- [npmgraph](http://npm.anvaka.com) - Visualization of dependencies.
- [npm trends](http://www.npmtrends.com) - Compare package download counts over time.
- [npm-compare](https://npmcompare.com) - Easily search and compare packages.
- [npm-top](https://gist.github.com/bcoe/dcc961b869bbf6685002) - npm users by downloads.
- [npm semver calculator](http://semver.npmjs.com) - Visually explore what versions of a package a semver range matches.
- [npm-stats](http://www.npm-stats.com) - Displays metrics about packages.
- [greenkeeper.io](http://greenkeeper.io) - Automates dependency updates through pull requests.
- [ghub.io](http://ghub.io) - Redirects to the GitHub repo of an npm package.
- [npm addict](https://npmaddict.com) - Your daily injection of npm packages.
- [npm discover](http://www.npmdiscover.com) - Discover what packages are commonly used together.
- [snyk](https://snyk.io) - Find, fix and monitor for known vulnerabilities in npm dependencies.

### Browser extensions

- [Octo-Linker](https://chrome.google.com/webstore/detail/octo-linker/jlmafbaeoofdegohdhinkhilhclaklkp) - Chrome extension to navigate across npm packages on GitHub with ease.
- [npm-hub](https://chrome.google.com/webstore/detail/npm-hub/kbbbjimdjbjclaebffknlabpogocablj) - Chrome extension to explore npm dependencies on GitHub repos.


## Packages

### Publishing

- [np](https://github.com/sindresorhus/np) - A better `npm publish`.
- [publish-please](https://github.com/inikulin/publish-please) - Publish packages safely and gracefully.
- [npm-release](https://github.com/phuu/npm-release) - Making releasing to npm so easy a kitten could probably do it™.
- [pkgfiles](https://github.com/timoxley/pkgfiles) - List all files which would be published in a package.
- [semantic-release](https://github.com/semantic-release/semantic-release) - Fully automated package publishing.

### Registry

- [npm-name](https://github.com/sindresorhus/npm-name-cli) - Check whether a package name is available on npm.
- [package-json](https://github.com/sindresorhus/package-json) - Get the package.json of a package from the npm registry.
- [latest-version](https://github.com/sindresorhus/latest-version-cli) - Get the latest version of an npm package.
- [npm-keyword](https://github.com/sindresorhus/npm-keyword) - Get a list of npm packages with a certain keyword.
- [npm-user](https://github.com/sindresorhus/npm-user) - Get user info of an npm user.
- [npm-email](https://github.com/sindresorhus/npm-email) - Get the email of an npm user.
- [npm-user-packages](https://github.com/kevva/npm-user-packages-cli) - Get packages by an npm user.
- [dpn](https://github.com/gillstrom/dpn) - Get the dependents of a user's npm packages.
- [npm-stats](https://github.com/hughsk/npm-stats) - Get data from an npm registry.
- [npm-cli-login](https://github.com/postmanlabs/npm-cli-login) - Log in to npm.
- [nrm](https://github.com/Pana/nrm) - Registry manager.

### Other

- [npm-home](https://github.com/sindresorhus/npm-home) - Open the npm page of a package.
- [gh-home](https://github.com/sindresorhus/gh-home) - Open the GitHub page of a package.
- [david](https://github.com/alanshaw/david) - Check if your package dependencies are out of date.
- [npm-check](https://github.com/dylang/npm-check) - Check for outdated, incorrect, and unused dependencies, as well as interactive update.
- [npm-shrinkwrap](https://github.com/uber/npm-shrinkwrap) - A consistent shrinkwrap tool.
- [npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) - Upgrade npm on Windows.
- [generator-nm](https://github.com/sindresorhus/generator-nm) - Scaffold out an npm package.
- [pkg-up](https://github.com/sindresorhus/pkg-up) - Find the closest package.json file.
- [read-pkg-up](https://github.com/sindresorhus/read-pkg-up) - Read the closest package.json file.
- [normalize-package-data](https://github.com/npm/normalize-package-data) - Normalize package metadata.
- [pkg-conf](https://github.com/sindresorhus/pkg-conf) - Get namespaced config from the closest package.json.
- [npm-run-path](https://github.com/sindresorhus/npm-run-path) - Run locally installed binaries in the terminal by name like with global ones.
- [local-npm](https://github.com/nolanlawson/local-npm) - Use npm [offline](https://addyosmani.com/blog/using-npm-offline/).
- [npe](https://github.com/zeke/npe) - CLI for inspecting and editing properties in package.json.
- [engine-deps](https://github.com/samccone/engine-deps) - Manage Node.js version specific dependencies with ease.
- [enpeem-search](https://github.com/amovah/enpeem-search) - Search packages by scraping the npm web search.
- [npm-issues](https://github.com/seanzarrin/npm-issues) - Search known issues of all your packages at once.
- [john](https://github.com/davej/john) - Make npm3's flat dependencies easier to find and sort.
- [ntl](https://github.com/ruyadorno/ntl) - Interactive CLI menu to list & run npm tasks.


## Clients

- [npm](https://github.com/npm/npm) - The official client.
- [ied](https://github.com/alexanderGugel/ied) - Faster npm.
- [pnpm](https://github.com/rstacruz/pnpm) - Performant `npm install`.


## Tips

### Update to the latest npm version

```
$ npm install --global npm
```

*[Windows users, read more.](https://github.com/felixrieseberg/npm-windows-upgrade)*

### Command aliases

- `npm i ` → `npm install`
- `npm i -S` → `npm install --save`
- `npm i -D` → `npm install --save-dev`
- `npm t` → `npm test`
- `npm it` → `npm install && npm test`
- `npm r` → `npm uninstall`

### Shell aliases

Speed up your common npm tasks.

In your `.zshrc`/`.bashrc`:

```sh
alias ni='npm install'
alias nis='npm install --save'
alias nid='npm install --save-dev'
alias nig='npm install --global'
alias nt='npm test'
alias nit='npm install && npm test'
alias nk='npm link'
alias nr='npm run'
alias nf='npm cache clean && rm -rf node_modules && npm install'
```


### Add to package.json when installing

You can have npm add packages to package.json when installing by specifying the `--save`/`-S` flag for `dependencies` and `--save-dev`/`-D` for `devDependencies`:

```
$ npm install --save chalk
```

### Run scripts

You can easily [run scripts](https://docs.npmjs.com/cli/run-script) using npm by adding them to the `"scripts"` field in package.json and run them with `npm run <script-name>`. Run `npm run` to see available scripts. Binaries of locally install packages are made available in the [PATH](https://en.wikipedia.org/wiki/PATH_(variable)), so you can run them by name. `npm run foo` will also run `prefoo` and `postfoo` if defined.

```json
{
	"name": "awesome-package",
	"scripts": {
		"cat": "cat-names"
	},
	"dependencies": {
		"cat-names": "^1.0.0"
	}
}
```

```
$ npm run cat
Max
```

All package.json properties are [exposed](https://docs.npmjs.com/misc/scripts#packagejson-vars) as environment variables:

```json
{
	"name": "awesome-package",
	"scripts": {
		"name": "echo $npm_package_name"
	}
}
```

```
$ npm run name
awesome-package
```


### Link local packages

Sometimes it can be useful to have a local version of a package as a dependency. You can use `npm link` to link one local package into another. Run `npm link` in the package you want to use. This creates a global reference. Then go into your original package and run `npm link <package-name>` to link in the other package.

```
$ cd rainbow
$ npm link
$ cd ../unicorn
$ npm link rainbow
```

You can now use `rainbow` as a dependency in the `unicorn` package.

### Install a package from GitHub

npm supports using a shorthand for installing a package directly from a GitHub repo:

```
$ npm install sindresorhus/chalk
```

Let's target a specific commit as master is a moving target:

```
$ npm install 'sindresorhus/chalk#51b8f32'
```

Specify either a commit SHA, branch, tag, or nothing.


### Install a specific version of a package

```
$ npm install chalk@1.0.0
```


### List top-level installed packages and their version

```
$ npm ls --depth=0
```

### Command help

Get help docs for a command:

```
$ npm help <command>
```

Example:

```
$ npm help install
```

### Standalone version of a package

Quickly get a standalone version of a package that is browserified and usable in the browser.

```
https://wzrd.in/standalone/<package-name>[@<version>]
```

Examples:

- https://wzrd.in/standalone/object-assign
- https://wzrd.in/standalone/object-assign@4.0.0

Great for prototyping, but download the file or use Browserify yourself for production.


## FAQ

- [Check in node_modules vs. shrinkwrap](http://stackoverflow.com/questions/11459733/check-in-node-modules-vs-shrinkwrap)
- [What is the difference between Bower and npm?](http://stackoverflow.com/questions/18641899/what-is-the-difference-between-bower-and-npm)
- [What does `^` mean in package.json versioning?](http://stackoverflow.com/questions/22137778/what-does-mean-in-package-json-versioning)
- [Find the version of an installed npm package](http://stackoverflow.com/questions/10972176/find-the-version-of-an-installed-npm-package)
- [What's the difference between dependencies, devDependencies, and peerDependencies in package.json?](http://stackoverflow.com/questions/18875674/whats-the-difference-between-dependencies-devdependencies-and-peerdependencies)


## Community

- [`#npm` on Freenode](http://webchat.freenode.net/?channels=npm)
- [Stack Overflow](http://stackoverflow.com/questions/tagged/npm)
- [Reddit](https://www.reddit.com/r/npm)
- [Twitter](https://twitter.com/npmjs)
- [Blog](http://blog.npmjs.org)


## Documentation

- [Official](https://docs.npmjs.com)
- [Troubleshooting](https://github.com/npm/npm/wiki/Troubleshooting)
- [Semantic versioning](https://docs.npmjs.com/getting-started/semantic-versioning)
- [Fixing npm permissions](https://docs.npmjs.com/getting-started/fixing-npm-permissions)
- [package.json](https://docs.npmjs.com/files/package.json)
- [npm run script](https://docs.npmjs.com/cli/run-script)
- [Stats API](https://github.com/npm/download-counts)


## Support

- [Issue tracker](https://github.com/npm/npm/issues)
- [Twitter](https://twitter.com/npm_support)
- [Contact form](https://www.npmjs.com/support)


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sindre Sorhus](http://sindresorhus.com) has waived all copyright and related or neighboring rights to this work.
