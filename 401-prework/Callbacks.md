# Do this when you're done please

## Callbacks

```Javascript

    // callback definition and usage example

    let myCallback = (data) {
        console.log(data);
    }

    let useCallback = (words, callback) => {
        console.log('1. Calling the CB');
        callback(words);
        console.log('2. Back from the CB')
    }

    useCallback('Hello', myCallback);
```

[Callbacks REPL](https://replit.com/@shadowdraco/Callbacks401Prework#index.js)
