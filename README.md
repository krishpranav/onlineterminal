# onlineterminal
A terminal in your browser using node.js and socket.io

[![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com)

# Installation
```
git clone https://github.com/krishpranav/onlineterminal
cd onlineterminal
sudo chmod +x *
sudo npm install
sudo npm run
```
# Example Code

```javascript
var tty = require('tty.js');

var app = tty.createServer({
  shell: 'bash',
  users: {
    foo: 'bar'
  },
  port: 8000
});

app.get('/foo', function(req, res, next) {
  res.send('bar');
});

app.listen();
```
