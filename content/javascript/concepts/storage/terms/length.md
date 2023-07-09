
---
Title: 'storage.length' property

Description: 'Returns a number representing the amount of data items stored in the Storage object.'

Subjects:
  - 'Web development'
  - 'API'
  - 'JSON'

Tags:
  - 'Algorithms'
  - 'Arithmetic'

CatalogContent:
  - 'learn-javascript'
  - 'paths/web development'
---

storage.length is a instance property of the object which it is called on. It will return the number of data items
(key/valve pairs) stored in a storage object and represent it as an integer. 

### Syntax
---
```
window.sessionStorage.length;
```
or 
```
window.localStorage.length;
```

As seen above the .length property can be used on either a localStorage object or a sessionStorage object.

### Example 
```
const createSessionObj = {
  "mytime", Date.now(),
  "myname", "David",
  "myage", 23
}; 

console.log(createSessionObj.length);
/// return 3

```
Here we have an object from the current session with it's stored key/value pairs. To find out how many the object is holding we can call .length on the object for the return value of 3. 

