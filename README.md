# angular4 support commands

**Update npm to latest version**
```
npm install -g npm@latest
```


**Update angular-cli to latest version (global)**
```
npm install -g @angular/cli@latest
```

**Update angular-cli to latest version (your project) - recommend to delete node_modules before**
```
npm install --save-dev @angular/cli@latest
```

**Update each dependency in package.json to the latest version**
```
npm i -g npm-check-updates
ncu -a
npm install
```

**Build app for production**
```
ng build --prod
```

**Install Electron**
```
npm install -g electron
npm install electron --save-dev
```

**Win Build Tools**
```
npm install --global --production windows-build-tools
```

**Set Environment to 32BUTS (need to reDownload everything)**
```
npm set npm_config_arch ia32
```
