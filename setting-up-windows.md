# Setting up your windows

## If you do not have Chrome, download and install it:
https://www.google.com/chrome/

## Recommended: download cmder and use it as command shell:
https://github.com/cmderdev/cmder/releases/download/v1.3.11/cmder.zip

After downloaded the zip file, unzip it and recommend put it under `C:\Applications` folder. Make sure you have file named: `C:\Applications\cmder\Cmder.exe`

Rum the Cmder.exe and pin it on task bar:
<pic>

## Sign up Github
* If you already have a github account send it to lihe.chen@gmail.com
* Otherwise Go to https://github.com/ , sign up a account with your email address, send the username to lihe.chen@gmail.com

## Install nvm
* Document here: https://github.com/coreybutler/nvm-windows
* Or click this link to download: https://github.com/coreybutler/nvm-windows/releases/download/1.1.7/nvm-setup.zip
* Unzip and Install

### Test nvm works:
* Open Cmder, run command:
```
nvm list available
```
The following should show:
<pic nvmlist>


## Install nodejs
* In cmder:
```
nvm install 10.15.3
```
* Set nodejs to use:
```
nvm use 10.15.3
```

### Test nodejs works:
```
node -v
```

## Install node http-server
```
npm i -g http-server
```
<pic install http-server>


## Install vscode: **recommended** most popular code editor
* Download and install vscode:
https://code.visualstudio.com/

## Serve your first html
* create your project folder, e.g `C:\projects`
```
mkdir C:\projects
```
* create your first html using vscode and save to `C:\projects`

### Run http-server under `C:\projects`
```
cd C:\projects
http-server
```
<pic http server>
Open chrome and browse to the url showed in red circle


