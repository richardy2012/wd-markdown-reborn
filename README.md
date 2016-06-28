# wd-markdown-reborn
This is an Electron tutorial app salvaged from a WebDesigner magazine article. The article's download did not supply a working app, but did supply a 95% gist of some apparently interim version of the code. Some screenshots provided motivation and clues on how to glue it together.

This app is a multi-tabbed markdown editor that uses Ace editor in edit mode and Marked in view mode. Use this app to see what you can do with Electron and as a starting point to expand the editor features.

Bootstrap and jQuery are installed via bower until I can figure how to bring it all under npm. When I installed them from npm, things fell apart.


## Using

You can build it yourself (see below).

## Building

You'll need [Node.js](https://nodejs.org) installed on your computer in order to build this app.

```bash
$ git clone https://github.com/chilismaug/wd-markdown-reborn.git
$ cd wd-markdown-reborn
$ npm install
$ npm start
```

For easier developing you can launch the app in fullscreen with DevTools open:

```bash
$ npm run dev
```
 

Follow [@ElectronJS](https://twitter.com/electronjs) on Twitter for important
announcements. Visit the [electron website](http://electron.atom.io).
