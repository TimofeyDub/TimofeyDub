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

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator</title>
    <link rel="stylesheet" href="style.css">
    <link rel="website icon" type="png" href="https://www.svgrepo.com/show/524345/calculator.svg">
</head>
<body >
    <div class="container">
        <h1 class="cal-text">Calculator</h1>
        <div class="calculator">
            <input type="text" id="display" disabled class="input-text"><br>
  <br>
  <input type="button" value="1" onclick="addToDisplay('1')" class="btn-n">
  <input type="button" value="2" onclick="addToDisplay('2')" class="btn-n">
  <input type="button" value="3" onclick="addToDisplay('3')" class="btn-n">
  <input type="button" value="+" onclick="addToDisplay('+')" class="btn-n">
  <br>
  <input type="button" value="4" onclick="addToDisplay('4')" class="btn-n">
  <input type="button" value="5" onclick="addToDisplay('5')" class="btn-n">
  <input type="button" value="6" onclick="addToDisplay('6')" class="btn-n">
  <input type="button" value="-" onclick="addToDisplay('-')" class="btn-n">
  <br>
  <input type="button" value="7" onclick="addToDisplay('7')" class="btn-n">
  <input type="button" value="8" onclick="addToDisplay('8')" class="btn-n">
  <input type="button" value="9" onclick="addToDisplay('9')" class="btn-n">
  <input type="button" value="*" onclick="addToDisplay('*')" class="btn-n">
  <br>
  <input type="button" value="C" onclick="clearDisplay()" class="btn-c">
  <input type="button" value="0" onclick="addToDisplay('0')" class="btn-n">
  <input type="button" value="=" onclick="calculate()" class="btn-r">
  <input type="button" value="/" onclick="addToDisplay('/')" class="btn-n">
    </div>
    <p style="color: white;">Created by <a href="https://github.com/TimofeyDub"><a style="color: rgb(0, 255, 0);">Dubinin</a> <a style="color: yellow;">Timofey</a></a></p>
        <a href="https://github.com/TimofeyDub"><button class="btn">My GitHub</button></a>
    </div>
  
    
    
  
  <script src="main.js"></script>
</body>
</html>
