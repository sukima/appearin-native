# Appear.in Native

Yes it can be done!

This repo is nothing more then a build script for [nativefier](). It will
create the icons (XCode needed) and then build the app using nativefier.

It is Mac OS X centric. Other platforms will require your own hacking of the
scripts.

## To build

1.  Install XCode
2.  Clone this repo and cd into it
3.  Run `npm install`
4.  Run `npm start`
5.  Final build will be in `build/Appear.in-darwin-x64`

The app can be moveed to `/Applications` if you wish.

For redistribution `npm run build-image` to make a DMG package.
