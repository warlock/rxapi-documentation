# Events

Files in "./sockets/events.js"

```javascript
module.exports = (socket, db) => {

  socket.on('hello', data => {
    console.log(`Hello ${data.name}`);
  });

};
```

