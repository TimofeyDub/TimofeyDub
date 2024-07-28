- 👋 Hi, I’m @TimofeyDub
- 👀 I’m interested in back-end
- 🌱 I’m currently learning express.js
- 📫 How to reach me Discord: @t1m0nyt

```js

const express = require('express')
const app = express()
const port = 3000

app.get('/', (req, res) => {
  res.send('Welcome to my profile!')
})

app.listen(port, () => {
  console.log(`Example app listening on port ${port}`)
})

```
