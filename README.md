# search-img-in-img

## Installation

```bash

$ npm install https://github.com/daniiltest/search-img-in-img
```

## Quick Example

```javascript
const { searchImg } = require('search-img-in-img')

const pathInImg = "inImg.png" // в каком изображении будем искать
const searchedImg = "search.png" // изображение которое будем искать

searchImg(pathInImg, searchedImg)
.then(res => {
	console.log(res)
	// res.status - содержит результат поиска: true/false (найдено или не найденно)
})
```
