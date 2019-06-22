## fetch

Request
Response

servie workers
Cache API

CORS
HTTP origin header
https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API

https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch

When using the fetch API it takes a url as an argument.
Then use a `.then()` method that takes a callback with response as an parameter. The response is the result of what is fetched from the URL. The function will return response.json(). An additional `.then()` is put onto the previous `.then()` with a callback that takes `myJson` as the parameter. At this point we convert the json information into information that could be understood.

fetch('http://example.com/movies.json')
.then(function(response) {
return response.json();
})
.then(function(myJson) {
console.log(JSON.stringify(myJson));
});

## endpoint

End point only returns a promise. A promise is saying that it will return data at a future date.

promise

prom

then()

blob of data

... spread into a array

regex
'gi' global insensitive

addEventListener('change', )
Change will detect if there are any chnages in the input.

addEventListener('keyup', )
