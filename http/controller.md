# Routes/Controller

Files in "./http/routes/users.js"

```javascript
const http = require('express').Router();

module.exports = db => {

  http.get('/firstUser', (req, res) => {
    db('users').insert({
      username: "username",
      surname: "surname",
      password: "password"
    })
    .then(res => {
      res.json(res)
    })
    .catch(err => {
      res.json(err)
    })
  });

  http.get('/bye', (req, res) => {
    res.json({ response : "bye" });
  });

  return http;
};
```

