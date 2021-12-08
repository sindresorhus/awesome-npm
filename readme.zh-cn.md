# Awesome npm [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [<img src="https://github.com/npm/logos/blob/7fb0bc425e0dac1bab065217c4ed595594448db4/npm-transparent.png" width="200" align="right" alt="npm">](https://www.npmjs.com)

> 优秀的 [npm](https://www.npmjs.com) 资源和技巧

[npm](https://en.wikipedia.org/wiki/Npm_(software)) 是一个 JavaScript 编程语言的包管理器，捆绑在 [Node.js](https://en.wikipedia.org/wiki/Node.js) 运行时中。

*在贡献之前，请阅读[贡献](contributing.md)指南。*


## 目录

- [文章](#文章)
- [工具](#工具)
- [包](#包)
- [客户端](#客户端)
- [技巧](#技巧)
- [FAQ](#faq)
- [社区](#社区)
- [文档](#文档)
- [支持](#支持)
- [关联](#关联)

## 文章

- [小型的重点模块](https://github.com/sindresorhus/ama/issues/10#issuecomment-117766328)
- [Unix哲学和 Node.js](http://blog.izs.me/post/48281998870/unix-philosophy-and-nodejs) - 编写只做一件事的程序，并把它做好。
- [编写小型模块](https://web.archive.org/web/20180302125059/https://substack.net/how_I_write_modules)
- [Semver: 初学者](https://nodesource.com/blog/semver-a-primer/) *(必读!)*
- [Semver: 波浪号和托字符](https://nodesource.com/blog/semver-tilde-and-caret/)
- [离线安装npm包](https://addyosmani.com/blog/using-npm-offline/)
- [用 npm run 实现任务自动化](https://web.archive.org/web/20180302164842/http://substack.net/task_automation_with_npm_run)
- [如何使用 npm 作为一个构建工具](https://www.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool/)
- [在 macOS 和 Linux 上无需 sudo 即可全局安装 npm 包](https://github.com/sindresorhus/guides/blob/main/npm-global-without-sudo.md)
- [优化 npm 包的体积](https://medium.com/@goldglovecb/npm-needs-a-personal-trainer-537e0f8859c6)
- [Node 的艺术](https://github.com/maxogden/art-of-node#modules) - 介绍 Node.js 和使用 npm 的客户端开发。
- [为什么用 npm scripts?](https://css-tricks.com/why-npm-scripts/) - 对 npm scripts 的介绍，包括常见的包和脚本，以及一个模板项目。

## 工具

### Web

- [npms](https://npms.io) - 超强的 npm 包搜索，使用[众多的指标](https://npms.io/about)对 npm 包质量进行深入分析。
	- [npm-introspect](http://npm-introspect.z3d.tech) - 一个基于npms的工具，用于直观地探索包依赖关系的质量。
- [node-modules](http://node-modules.com) - 基于你的 GitHub 社交图谱的个性化包搜索。
- [NodeICO](https://nodei.co/) - Package 徽章。
- [Libraries.io](https://libraries.io/npm) - Package 探索。
- [npm-stat](http://npm-stat.com) - Package 的统计图表。
- [npmgraph](http://npm.anvaka.com) - 依赖关系的可视化。
- [npm trends](http://www.npmtrends.com) - 比较一段时间内的 Package 下载数量。
- [npm-compare](https://npmcompare.com) - 轻松搜索和比较 Package。
- [npm-top](https://gist.github.com/bcoe/dcc961b869bbf6685002) - npm 用户的下载量。
- [npm semver calculator](http://semver.npmjs.com) - 可视化地探索一个 semver 范围内的包的哪些版本相匹配。
- [ghub.io](https://ghub.io) - 重定向到一个 npm 包的 GitHub repo。
- [npm addict](https://npmaddict.com) - 你每天的 npm package 的注入。
- [moiva](https://moiva.io) - 发现并比较 Package。
- [Openbase](https://openbase.com) - 用强大的指标和用户评论来比较开源 Package。

### 浏览器扩展

- [Octo-Linker](https://chrome.google.com/webstore/detail/octo-linker/jlmafbaeoofdegohdhinkhilhclaklkp) - 可以轻松地浏览 GitHub 上的 npm 包的 Chrome 扩展。
- [npm-hub](https://chrome.google.com/webstore/detail/npm-hub/kbbbjimdjbjclaebffknlabpogocablj) - 探索 GitHub 仓库的 npm 依赖性的 Chrome 扩展。
- [github-npm-stats](https://chrome.google.com/webstore/detail/github-npm-stats/oomfflokggoffaiagenekchfnpighcef) - 在 GitHub 上查看 npm 的下载统计。
- [npm-search-update](https://chrome.google.com/webstore/detail/npm-search-update/kagpoplamlmaonpddimnnigiojimihnh) - 可以快速搜索依赖性，并监控 npm 注册表的变化的 Chrome 扩展。

### CLI

- [zsh-better-npm-completion](https://github.com/lukechilds/zsh-better-npm-completion) - 为 npm 提供更好的 ZSH 完成度。
- [npkill](https://github.com/voidcosmos/npkill) - 轻松地找到并删除旧的和沉重的 node_modules 文件夹。

## 包

### 发布

- [np](https://github.com/sindresorhus/np) - 一个更好的 `npm publish`.
- [publish-please](https://github.com/inikulin/publish-please) - 安全、优雅地发布包。
- [npm-release](https://github.com/phuu/npm-release) - 让发布到 npm 的工作变得如此简单，小猫都可以做到™。
- [pkgfiles](https://github.com/timoxley/pkgfiles) -  列出将在一个包中发布的所有文件。
- [release-it](https://github.com/webpro/release-it) - 为 Git 仓库和/或 npm 包自动发布。Changelog 的生成，GitHub/GitLab 的发布，等等。
- [semantic-release](https://github.com/semantic-release/semantic-release) - 全自动化的包发布。

### 仓库

- [npm-name](https://github.com/sindresorhus/npm-name-cli) - 检查一个包的名称在npm上是否可用。
- [package-json](https://github.com/sindresorhus/package-json) - 从npm注册表中获取一个包的 package.json。
- [latest-version](https://github.com/sindresorhus/latest-version-cli) - 获取一个 npm 包的最新版本。
- [npm-keyword](https://github.com/sindresorhus/npm-keyword) - 获取带有某个关键词的 npm 包的列表。
- [npm-user](https://github.com/sindresorhus/npm-user) - 获取一个 npm 用户的用户信息。
- [npm-email](https://github.com/sindresorhus/npm-email) - 获取一个 npm 用户的电子邮件。
- [npm-user-packages](https://github.com/kevva/npm-user-packages-cli) - 通过一个 npm 用户获取包。
- [dpn](https://github.com/gillstrom/dpn) - 获取一个用户的 npm 包的依赖项。
- [npm-stats](https://github.com/hughsk/npm-stats) - 从一个 npm 注册表中获取数据。
- [npm-cli-login](https://github.com/postmanlabs/npm-cli-login) - 登录到 npm。
- [nrm](https://github.com/Pana/nrm) - npm 源管理.
- [npm-register](https://github.com/dickeyxxx/npm-register) - 易于设置和维护 npm 注册表和代理。
- [verdaccio](https://github.com/verdaccio/verdaccio) - 轻量级私有 npm 代理注册中心。
- [cloudsmith](https://cloudsmith.io/l/npm-registry/) - 一个完全管理的包管理 SaaS，支持公共和私人 npm 注册（以及许多其他功能）。

### 其他

- [npm-home](https://github.com/sindresorhus/npm-home) - 打开一个包的 npm 主页。
- [gh-home](https://github.com/sindresorhus/gh-home) - 打开一个包的 GitHub 页面。
- [david](https://github.com/alanshaw/david) - 检查你的包的依赖性是否已经过期。
- [npm-check](https://github.com/dylang/npm-check) - 检查过时的、不正确的和未使用的依赖，以及交互式更新。
- [npm-upgrade](https://github.com/th0r/npm-upgrade) - 以交互方式更新过时的 npm 依赖关系。
- [npm-shrinkwrap](https://github.com/uber/npm-shrinkwrap) - 一个表现一致的 shrinkwrap 工具。
- [npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) - 在 Windows 上升级 npm。
- [generator-nm](https://github.com/sindresorhus/generator-nm) - 搭建一个 npm 包的脚手架。
- [pkg-up](https://github.com/sindresorhus/pkg-up) - 找到最近的 package.json 文件。
- [read-pkg-up](https://github.com/sindresorhus/read-pkg-up) - 读取最近的 package.json 文件。
- [normalize-package-data](https://github.com/npm/normalize-package-data) - 规范化包的元数据。
- [pkg-conf](https://github.com/sindresorhus/pkg-conf) - 从最近的 package.json 中获取命名的配置。
- [npm-run-path](https://github.com/sindresorhus/npm-run-path) - 在终端运行本地安装的二进制文件，就像运行全局的二进制文件一样，以名字命名。
- [local-npm](https://github.com/nolanlawson/local-npm) - [离线](https://addyosmani.com/blog/using-npm-offline/) 使用 npm。
- [npe](https://github.com/zeke/npe) - 用于检查和编辑 package.json 中的属性的 CLI。
- [engine-deps](https://github.com/samccone/engine-deps) - 轻松地管理 Node.js 的特定版本依赖。
- [enpeem-search](https://github.com/amovah/enpeem-search) - 通过搜刮 npm 的网络搜索来搜索包。
- [npm-issues](https://github.com/seanzarrin/npm-issues) - 一次性搜索你所有包的已知问题。
- [john](https://github.com/davej/john) - 让 npm3 的平铺依赖关系更容易找到和排序。
- [ntl](https://github.com/ruyadorno/ntl) - 交互式CLI菜单，列出并运行 npm 任务。
- [decheck](https://github.com/egoist/decheck) - 在命令行中探索 npm 包的依赖性。
- [shrinkpack](https://github.com/JamieMason/shrinkpack) - 锁定你的依赖关系并进行离线安装。
- [redrun](https://github.com/coderaiser/redrun) - 从 package.json 扩展脚本，以提高执行速度。
- [package-size](https://github.com/egoist/package-size) - 获取一个 npm 包的包体大小。
- [synp](https://github.com/imsnif/synp) - 将 yarn.lock 转换成 package-lock.json，反之亦然。
- [npm-run-all](https://github.com/mysticatea/npm-run-all) - 一个可以并行或串行地运行多个 npm-scripts 的 CLI 工具。
- [onchange](https://github.com/Qard/onchange) - 观察文件和文件夹，当有变化时运行一个命令。
- [cli-error-notifier](https://github.com/micromata/cli-error-notifier) - 当 npm 脚本失败时，发送本地桌面通知。
- [luna](https://github.com/rvpanoz/luna) - 管理 npm 依赖关系的应用程序。
- [emma-cli](https://github.com/maticzav/emma-cli) - 交互式 CLI 包搜索工具。
- [lockfile-lint](https://github.com/lirantal/lockfile-lint) - 为提高安全性和信任政策而对锁文件进行过滤，以减轻恶意的包注入和不安全的 lock 文件资源。

## 客户端

- [yarn](https://github.com/yarnpkg/yarn) - 快速、可靠、安全的依赖性管理。
- [npm](https://github.com/npm/cli) - 官方客户端。
- [pnpm](https://github.com/pnpm/pnpm) - 快速、磁盘空间高效的包管理器。

## 技巧

### 更新到最新的 npm 版本

```
$ npm install --global npm
```

*[Windows用户，请阅读更多。](https://github.com/felixrieseberg/npm-windows-upgrade)*

### 命令别名

- `npm i ` → `npm install`
- `npm i -D` → `npm install --save-dev`
- `npm t` → `npm test`
- `npm it` → `npm install && npm test`
- `npm r` → `npm uninstall`
- `npm un` → `npm uninstall`
- `npm up` → `npm update`

### Shell 别名

加快你的公共 npm 任务。

如果你使用 `.zshrc`/`.bashrc`:

```sh
alias ni='npm install'
alias nid='npm install --save-dev'
alias nig='npm install --global'
alias nt='npm test'
alias nit='npm install && npm test'
alias nk='npm link'
alias nr='npm run'
alias ns='npm start'
alias nf='npm cache clean && rm -rf node_modules && npm install'
alias nlg='npm list --global --depth=0'
```

### 安装时不要添加到 package.json 中

默认情况下，npm 会将你安装的包添加到 package.json 的 `dependencies` 中（从v5开始）。你可以通过指定 `--no-save` 标志来防止这一点。你可以用 `--save-dev/-D` 将包添加到 `devDependencies` 中。

```
$ npm install --save-dev ava
```

### 运行 scripts

你可以使用 npm 轻松地[运行脚本](https://docs.npmjs.com/cli/run-script)，把它们添加到 package.json 中的 `"scripts"` 字段中，然后用 `npm run <script-name>` 运行它们。运行 `npm run` 可以看到可用的脚本。本地安装的包的二进制文件在[PATH](https://en.wikipedia.org/wiki/PATH_(variable))中是可用的，所以你可以按名称运行它们。

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

所有 package.json 属性都作为环境变量[暴露](https://docs.npmjs.com/misc/scripts#packagejson-vars)出来:

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

#### 将选项传递给命令

`--` 标志着[选项解析的结束](https://unix.stackexchange.com/questions/11376/what-does-double-dash-mean-also-known-as-bare-double-das)，所以 `npm run` 会直接忽略它并将其传递给命令。

```json
{
	"name": "awesome-package",
	"scripts": {
		"xo": "xo",
		"xo:fix": "npm run xo -- --fix",
	}
}
```

*添加 `-- --fix ` 修复选项就像执行 `xo --fix` 修复*。

#### 沉默选项

`npm run` 有一个 `--silent` 选项，在组合 npm 脚本时特别有用。

想象一下，你有一个设置，用于对你的 JavaScript 文件进行刷新，如下所示:

```json
{
	"name": "awesome-package",
	"scripts": {
		"xo": "xo",
		"xo:fix": "npm run xo --silent -- --fix",
	}
}
```

*使用 `--silent` 选项可以减少终端中的输出。请看这个比较。*

### scripts 生命周期

npm 带有预定义的[生命周期脚本](https://docs.npmjs.com/misc/scripts)，如果这些脚本在你的 package.json 中定义，就会在特定条件下被切除。

```json
{
	"name": "awesome-package",
	"scripts": {
		"prepublishOnly": "nsp check"
	},
	"devDependencies": {
		"nsp": "^3.0.0"
	}
}
```

这将在你的 npm 包通过 `npm publish` 发布到注册表之前自动执行，以检查你的依赖中的已知漏洞。

*笔记: **prepublishOnly** 从 npm v4.0.0 开始可用，参见[npm 文档](https://docs.npmjs.com/misc/scripts#deprecation-note)。*

#### `npm start` 和 `npm test`

`npm start` 和 `npm test` 也是生命周期脚本，但不会自动执行。

```json
{
	"name": "awesome-package",
	"scripts": {
		"start": "node server.js",
		"test": "ava"
	},
	"devDependencies": {
		"ava": "^1.0.0"
	}
}
```

因此，它们可以简单地用以下方式执行:

```console
$ npm test
$ npm start
```

#### `pre` 和 `post` 脚本

这些是特殊的生命周期脚本，可以用来依次自动运行脚本。

```json
{
	"name": "awesome-package",
	"scripts": {
		"pretest": "eslint .",
		"test": "ava"
	},
	"devDependencies": {
		"eslint": "^4.19.0",
		"ava": "^1.0.0"
	}
}
```

```console
$ npm test
```

这将在运行测试前对你的文件进行提示。如果润色失败，测试将不会运行。或者更笼统的说：如果依次运行的脚本中有一个退出代码不是 0，下面的脚本将不会被执行。

*笔记: `pre` 和 `post` 脚本也可以用于你的自定义 npm 脚本。所以 `npm run foo` 也会运行`prefoo` 和 `postfoo` ，如果定义了的话。*

### 用 `npx` 运行脚本

`npm` 与 `npx` [绑定在一起](https://medium.com/@maybekatz/introducing-npx-an-npm-package-runner-55f7d4bd282b) （从v5.2.0开始）-- 一个执行包二进制文件的工具。每条命令要么从本地 `node_modules/.bin` 目录中执行，要么从中央缓存中执行，安装 `<command>` 运行所需的任何包。

```json
{
	"name": "awesome-package",
	"dependencies": {
		"cat-names": "^1.0.0"
	}
}
```

如果二进制文件已经安装，它将从`node_modules/.bin`执行。

```
$ npx cat-names
Max
```

但如果缺少二进制文件，就会先安装它。

```
$ npx dog-names
npx: installed 46 in 3.136s
Bentley
```

### 用不同的 Node.js 版本运行命令

有了 `npx` （与npm v5.2.0或更新的版本捆绑在一起）和 [`node-bin`](https://www.npmjs.com/package/node-bin) 包，你可以轻松地尝试不同 Node.js 版本的代码，而不必使用像 [`nvm`](http://nvm.sh)、[`nave`](https://github.com/isaacs/nave) 或 [`n`](https://github.com/tj/n) 这样的版本管理器。

```
$ npx --package=node-bin@6.11.0 -- node --version
v6.11.0
```

### 链接本地包

有时，将一个本地版本的包作为依赖关系是很有用的。你可以使用 `npm link` 将一个本地包链接到另一个。在你想使用的包中运行 `npm link`。这将创建一个全局参考。然后进入你的原始包，运行 `npm link <package-name>` 来链接另一个包。

```
$ cd rainbow
$ npm link
$ cd ../unicorn
$ npm link rainbow
```

现在你可以使用 `rainbow` 作为 `unicorn` 包的依赖项。

### 从 GitHub 上安装一个包

npm支持使用速记法来直接从 GitHub 仓库中安装一个包。

```
$ npm install sindresorhus/chalk
```

让我们以特定的提交为目标，因为主分支是一个移动的目标。

```
$ npm install 'sindresorhus/chalk#51b8f32'
```

指定一个提交 SHA、分支、标签，或者什么都不指定。

你也可以用 semver 安装 Git 的依赖项。*（需要 npm v5 或更新版本）*。

```
$ npm install 'sindresorhus/chalk#semver:^2.0.0'
```

### 安装一个特定版本的包

```
$ npm install chalk@1.0.0
```


### 列出顶级安装的包和它们的版本

```
$ npm ls --depth=0
```

### 帮助命令

获取一个命令的帮助文档:

```
$ npm help <command>
```

例子:

```
$ npm help install
```

### 包的独立版本

快速获得一个独立版本的包，该包已被浏览器化，可在浏览器中使用。

```
https://wzrd.in/standalone/<package-name>[@<version>]
```

例子:

- <https://wzrd.in/standalone/object-assign>
- <https://wzrd.in/standalone/object-assign@4.0.0>

很适合做原型设计，但要下载文件或自己使用 Browserify 进行生产。

## FAQ

- [在 node_modules 与 shrinkwrap 中进行检查](http://stackoverflow.com/questions/11459733/check-in-node-modules-vs-shrinkwrap)
- [Bower 和 npm 之间的区别是什么？](http://stackoverflow.com/questions/18641899/what-is-the-difference-between-bower-and-npm)
- [`^` 在 package.json 版本管理中是什么意思？](http://stackoverflow.com/questions/22137778/what-does-mean-in-package-json-versioning)
- [查找已安装的 npm 包的版本](http://stackoverflow.com/questions/10972176/find-the-version-of-an-installed-npm-package)
- [package.json 中的 dependencies、devDependencies 和 peerDependencies 有什么区别？](http://stackoverflow.com/questions/18875674/whats-the-difference-between-dependencies-devdependencies-and-peerdependencies)

## 社区

- [`#npm` 话题在 Freenode](http://webchat.freenode.net/?channels=npm)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/npm)
- [Reddit](https://www.reddit.com/r/npm)
- [Twitter](https://twitter.com/npmjs)
- [Blog](https://blog.npmjs.org)

## 文档

- [官方](https://docs.npmjs.com)
- [Troubleshooting](https://github.com/npm/npm/wiki/Troubleshooting)
- [语义化版本](https://docs.npmjs.com/getting-started/semantic-versioning)
- [修复npm权限](https://docs.npmjs.com/getting-started/fixing-npm-permissions)
- [package.json](https://docs.npmjs.com/files/package.json)
- [npm 运行脚本](https://docs.npmjs.com/cli/run-script)
- [统计 API](https://github.com/npm/download-counts)

## 支持

- [npm.community](https://npm.community/c/support)
- [Twitter](https://twitter.com/npm_support)
- [联系表单](https://www.npmjs.com/support)

## 关联

- [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs)
