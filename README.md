# ep-133 sample tool offline version

## Requirements

npm
electron
~~electron-builder~~
  - i think it does it automatically now? need to test on a clean system

## How to build

after requirements are installed, simply run:
```
npm run package
```

all build files are in the `dist` directory.

## How to run without building

you do not need `electron-builder` to run. all you need is npm and electron installed.
```
npm start
```
