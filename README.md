amplify.when
============

An extension for AmplifyJS that uses When.js promises.

## Example usage

`amplify.request` returns a When.js promise:

```
amplify.request("my-request", {
    data: 1
})
.then(function success(response) {
    
}, function failure(error) {

});
```
