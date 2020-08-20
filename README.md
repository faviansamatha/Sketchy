# Sketchy

![logo](/img/logo.png)

Sketchy is a multiplayer pictionary-like web game. This was created for CMPT276's semester-long project

## Demo Video Link:
https://www.youtube.com/watch?v=-X_ICjygmzo&fbclid=IwAR1SF7EvtXodxercaOkNHyqpBOM-yeHMJIqpqS77s3s76jR8JRFQXmGXnh8

## App Heroku Link: 
https://sketchy-app-production.herokuapp.com/


### For local testing:

Index.js:
Line 607 must be: const io = require('socket.io')(3000);

Socket.js:
Uncomment: const socket = io('http://localhost:3000’);
Comment out the server line.

### to run tests, run:
```npm test```

to run locally, ensure dependencies are installed and run:
```npm run devStart```

### Authors

- [Benjamin Katz](https://github.com/ben-katz)
- [Zhifan (Van) Shen](https://github.com/ZhifanShen)
- [Favian (Ian) Samatha](https://github.com/faviansamatha)
- [Daisy Xu](https://github.com/daiisyx)
- [Michael Chang](https://github.com/engichang1467)

