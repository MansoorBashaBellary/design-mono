Error: Command failed: git log --oneline --pretty=%h;%D;%s;%cd --date=short v1.0.0..HEAD
fatal: ambiguous argument 'v1.0.0..HEAD': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'


    at makeError (/Users/mbellary/Desktop/mansoor-github/design-mono/node_modules/lerna-changelog/node_modules/execa/index.js:172:9)
    at Function.module.exports.sync (/Users/mbellary/Desktop/mansoor-github/design-mono/node_modules/lerna-changelog/node_modules/execa/index.js:341:15)
    at Object.listCommits (/Users/mbellary/Desktop/mansoor-github/design-mono/node_modules/lerna-changelog/lib/git.js:67:10)
    at Changelog.getListOfCommits (/Users/mbellary/Desktop/mansoor-github/design-mono/node_modules/lerna-changelog/lib/changelog.js:142:20)
    at Changelog.<anonymous> (/Users/mbellary/Desktop/mansoor-github/design-mono/node_modules/lerna-changelog/lib/changelog.js:86:40)
    at step (/Users/mbellary/Desktop/mansoor-github/design-mono/node_modules/lerna-changelog/lib/changelog.js:32:23)
    at Object.next (/Users/mbellary/Desktop/mansoor-github/design-mono/node_modules/lerna-changelog/lib/changelog.js:13:53)
    at /Users/mbellary/Desktop/mansoor-github/design-mono/node_modules/lerna-changelog/lib/changelog.js:7:71
    at new Promise (<anonymous>)
    at __awaiter (/Users/mbellary/Desktop/mansoor-github/design-mono/node_modules/lerna-changelog/lib/changelog.js:3:12)
