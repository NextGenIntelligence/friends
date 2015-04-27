# Friends

p2p chat powered by the web. **alpha quality** you probably only want to use this if you like to send pull requests fixing things :)

[![travis][travis-image]][travis-url]

[travis-image]: https://img.shields.io/travis/moose-team/friends.svg?style=flat
[travis-url]: https://travis-ci.org/moose-team/friends

## Logging in

You need a working git + github configuration

- have a publicly listed github email (e.g. shows up on your github account)
- if you dont wanna do that then do `git config --global user.username yourusername`

When you launch the app it should "just work" now if you have git setup correctly :)

## Building

You'll need the newest io.js and npm (`>= 1.8.1`, `>= 2.8.3`)

* `git clone git@github.com:moose-team/friends`
* `cd friends`
* `npm install`
* `cd app && npm run rebuild` to compile leveldown for electron
* `cd ..` to go back to the root folder
* `npm start` to run in electron
* `npm run package` to build distributable.

## License

[CC-0](LICENSE.md)
