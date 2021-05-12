# Samaya

Samaya is a productivity focused chrome extension highly inspired by Momentum. It's not intended to be a clone but an improvement with more Nepali feeling and simplicity.

## View the extension here
https://chrome.google.com/webstore/detail/samaya/jmpipanemahgfelokjjpdilfcfboinni

Chrome web store has the incomplete version. If you want to use the latest one please follow the instructions below to build use it locally.

## Key Features
- Nepali Language
- Simple/Clear/Minimal user interface
- Nepali Calendar
- Notes app

## Project setup & deployement

### Setup
```
npm install

npm run serve
```

### Deployemnt to chrome extensions

```
npm run build

// To install on chrome
- Goto Chrome->Extensions->Load Unpacked
- Point to 'dist' directory inside your project
- After each build, reload extension 
```

### Todos
- [ ] Consistemt design System
- [ ] Functional calendar
- [ ] Select best image sources from Unsplash
- [x] Build static JSON quotes api(splits data into chunks - chunk_1.json, chunk_2.json...)
- [ ] Application settings
- [ ] Pomodoro Timer (Break work into chunks, 25 minutes work, 5 minutes btreak, repeat 4 cycles, take a longer break, track how long each task takes)