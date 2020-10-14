NeuroKeeper
======================

## How to start the app:

```
npm i
npm start
```

*If you encount errors on* ```node-gyp rebuild```*, you need some additional libraries to be installed:*

```
sudo apt-get install libxext-dev libxtst-dev libxkbfile-dev
```

## How to publish the app:

```
npm run publish
```

## How to build installer for Debian\Ubuntu:
- execute `npm run package-linux`
- execute `npm run create-debian-installer`
- find *.deb file into ```/release-builds folder```

## [More info about auto update](https://www.electron.build/auto-update)
