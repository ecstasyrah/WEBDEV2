### API (Application Programming Interface)
**middle man between client and the database**
* you wont directly connect with the database
* everything has an API
* post request can't be seen on url
> fetch('https://jsonplaceholder.typicode.com/todos/1')
      .then(response => response.json())
      .then(json => console.log(json))
* get data from **response** then return to **json**
* ".then" is asynchronous
