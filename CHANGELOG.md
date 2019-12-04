Error: Command failed: git log --oneline --pretty=%h;%D;%s;%cd --date=short 1.0.0..HEAD
fatal: ambiguous argument '1.0.0..HEAD': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'


    at makeError (/Users/siriwatkunaporn/.config/yarn/global/node_modules/execa/index.js:174:9)
    at Function.module.exports.sync (/Users/siriwatkunaporn/.config/yarn/global/node_modules/execa/index.js:338:15)
    at Object.listCommits (/Users/siriwatkunaporn/.config/yarn/global/node_modules/lerna-changelog/lib/git.js:68:10)
    at Changelog.getListOfCommits (/Users/siriwatkunaporn/.config/yarn/global/node_modules/lerna-changelog/lib/changelog.js:143:20)
    at Changelog.<anonymous> (/Users/siriwatkunaporn/.config/yarn/global/node_modules/lerna-changelog/lib/changelog.js:87:40)
    at step (/Users/siriwatkunaporn/.config/yarn/global/node_modules/lerna-changelog/lib/changelog.js:33:23)
    at Object.next (/Users/siriwatkunaporn/.config/yarn/global/node_modules/lerna-changelog/lib/changelog.js:14:53)
    at /Users/siriwatkunaporn/.config/yarn/global/node_modules/lerna-changelog/lib/changelog.js:8:71
    at new Promise (<anonymous>)
    at __awaiter (/Users/siriwatkunaporn/.config/yarn/global/node_modules/lerna-changelog/lib/changelog.js:4:12)
