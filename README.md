amplify.when
============

An extension for AmplifyJS that uses When.js promises.

## Example usage

`amplify.request` returns a When.js promise:

```javascript
amplify.request("my-request", {
    data: myData
})
.then(function success(response) {
    
}, function failure(error) {

});
```
