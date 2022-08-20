[Home](/README.md)

# Class 13 - Local Storage

## Local Storage and How To Use It On Websites

1. Why would a developer use local storage for a web application?  
    Local storage makes it possible for the developer to store the "state" of an application so that it does not reset when the browser is closed and re-opened.
2. What information should not be stored in local storage?  
    Sensitive information such as passwords or personal information should not be stored in local storage.
3. Local storage can store what type of data? How would you convert it to that type before storing?  
    Local storage stores all data as strings. We can convert our data using `JSON.stringify()` method.