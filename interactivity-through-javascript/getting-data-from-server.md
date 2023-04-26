# Getting data from Server

To get data from a server using JavaScript, you can use the `XMLHttpRequest` object or the `fetch` function.

Here is an example of how to use the `XMLHttpRequest` object to make a GET request to a server and retrieve data:

```javascript
var xhr = new XMLHttpRequest();
xhr.open("GET", "http://example.com/data.json");
xhr.onload = function() {
  if (xhr.status == 200) {
    // success
    var data = JSON.parse(xhr.responseText);
    console.log(data);
  } else {
    // error
    console.error(xhr.statusText);
  }
};
xhr.onerror = function() {
  console.error(xhr.statusText);
};
xhr.send();
```

Here is an example of how to use the `fetch` function to make a GET request to a server and retrieve data:

```javascript
fetch("http://example.com/data.json")
  .then(function(response) {
    return response.json();
  })
  .then(function(data) {
    console.log(data);
  })
  .catch(function(error) {
    console.error(error);
  });
```

Both `XMLHttpRequest` and `fetch` allow you to make requests to a server and receive data in the form of a response. They are widely used in web development to retrieve data from a server asynchronously and to update a webpage without reloading it.

Note that these examples use JSON as the data format, but you can also use other formats such as XML, PDF, Text and so on.
