
# Express JS

> request and response cycle
>
> to complete the cycle. send a req, then should send a response.
> 

### Post
> request do not have data stored in the URL. cant cache data outside unlike get

## Postman (download)
> different methods, different results
- ![image](https://github.com/ecstasyrah/WEBDEV2/assets/126046661/78353376-eca2-4ef1-864b-bf5cbfadeb18)
- ![image](https://github.com/ecstasyrah/WEBDEV2/assets/126046661/27ad6fd4-56f9-4a5c-9832-80cae5bc3f23)

> body -> raw
>
> Text -> JSON
>
> header -> content-type:"application/json" (_JSON format_)

- fetch("http://localhost:3000/addStudent",{ method: "POST", headers:{content-type: "application/json"}, body:{"id"=4}, "name": "Josh", "age": 27}})

### others
- default method : **get**
- return : **short circuit a function** (inside a request)
  - to make sure that after we send data we end callback function
- copy pasta
  - https://pastebin.com/15Gqamtv
