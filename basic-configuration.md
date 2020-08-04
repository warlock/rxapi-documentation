# Basic configuration

File "./config.js":

```javascript
module.exports = {
  http_port: 3000,
  sockets_port: 3001,
  mode: 'development', // knex database configuration
  public : {
    enable : true,
    folder : 'public'
  },
  cors : true,
  sockets : true
};
```

