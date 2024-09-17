## Fetching data
fetch() on its own returns a promise and a promise is an object 
```JavaScript
fetch('https://jsonplaceholder.typicode.com/posts') //returns a promise
  .then((response) => response.json()) //turn what you have fetched into JavaScript
  .then((json) => console.log(json)); //console.log the data that you have turned into JavaScript
  ```