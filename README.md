# electron-tutorial
Trying to learn how to build apps using electron


## Basic steps

1. Install Node
2. Create project directory and browse into it
3. npm init
4. node install electron --save
5. Add the following code in index.js
  ```javascript
  const electron = require('electron')
  const {app, BrowserWindow} = electron


  app.on('ready', () => {
    let win = new BrowserWindow({width : 800, height: 600})
    win.loadURL(`http:\\www.dhawalverma.com`)
  })
  ```
6. Test the app by running the command electron . on terminal
