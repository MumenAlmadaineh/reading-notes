# Local storage in JavaScript

![Local storage in JavaScript Photo](https://res.cloudinary.com/de4rvmslk/image/upload/f_auto,q_auto/LocalStorage-cover_photo.png)

## What is mean Local storage?

Local storage in JavaScript is a property that allows JavaScript sites and apps to save key-value pairs in a web browser with no expiration date.

- This means the data stored in the browser will persist even after the browser window is closed.

- We can start using local storage by using a method `window.localStorage`

## What is Window.localStorage?

> (logrocket) The localStorage mechanism is available via the Window.localStorage property. Window.localStorage is part of the Window interface in JavaScript, which represents a window containing a DOM document.

for example:

```
if (typeof(Storage) !== "undefined") {
  // Code for localStorage/sessionStorage.
} else {
  // Sorry! No Web Storage support..
}
```

There are five properties we use it local storage to store data:

1. `setItem()` Add key and value to `localStorage`.

2. `getItem()` This is how you get items from `localStorage`

3. `removeItem()` Remove an item by key from `localStorage`

4. `clear()` Clear all `localStorage`

5. `key()` Passed a number to retrieve the key of a `localStorage`

![Local storage in JavaScript Photo](https://lh3.googleusercontent.com/proxy/RIfcQb3oGPLw0whYNIJXujVcidCahfZG3RyoS75KhwjstdcDGM1TEiRFwfEGojlGgBiYxYhlVfIwWR4VSC0pKjdqrt61yVcwEzL3ahistRF90SrW3r-gQFSI11xz)

## The localStorage Object

![Local storage in JavaScript Photo](https://res.cloudinary.com/practicaldev/image/fetch/s--NVPk20-f--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/2imjutnczd4f3jdhgbdx.png)

> (w3schools) The localStorage object stores the data with no expiration date. The data will not be deleted when the browser is closed, and will be available the next day, week, or year.

for example:

```
// Store
localStorage.setItem("lastname", "Smith");

// Retrieve
document.getElementById("result").innerHTML = localStorage.getItem("lastname");
```

This part of the code we need to add it to the foot of our body element:

> (w3schools) Example explained:
>
> - Create a localStorage name/value pair with name="lastname" and value="Smith"
> - Retrieve the value of "lastname" and insert it into the element with id="result"

The example above could also be written like this:

```
// Store
localStorage.lastname = "Smith";
// Retrieve
document.getElementById("result").innerHTML = localStorage.lastname;
```

- The syntax for removing the "lastname" localStorage item is as follows:

`localStorage.removeItem("lastname");`

[If you want learn more about How to use Local Storage in JavaScript we recommend you to watch this video](https://www.youtube.com/watch?v=k8yJCeuP6I8)
