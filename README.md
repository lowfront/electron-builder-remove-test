# electron-builder-remove-test

`nsis.deleteAppDataOnUninstall` property malfunction if package.json's name property is scoped.

## Start

```
npm i
npm start
```

After the build, run the installation file `build/electron-builder-testSetup1.0.exe` to install and remove the program, The folder `C:\Users\%username%\AppData\Roaming\@lowfront\electron-builder-remove-test` remains undeleted.
