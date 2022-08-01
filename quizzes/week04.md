# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
synchronous means the code all runs together at the time it is read, async on the other hand, is run at a different time.
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
It is like a setTimeout in that it runs the functions given to it as parameters but instead of running at regular intervals a listener watches for changes to a specified file or object and runs the code when the object is changed. I imagine that there are other kinds of listeners that are more 
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The open–closed principle: "Software entities ... should be open for extension, but closed for modification."
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
a callback function is a function that is passed into another function as an argument. This function can then be invoked during the execution of that higher order function (that it is an argument of). Since, in JavaScript, functions are objects, functions can be passed as arguments.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
a Promise is an object with three states: pending, resolved, and rejected. promises are used to deal with asynchronous operations in JavaScript. a promise is a guarantee that we are going to do something in the future.
to capture an error you attach a catch() stated as an if within the promise which runs in the case that the promise is rejected.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
post(create), get(read), put(update), delete(destroy)
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application Programming Interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```

```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
To prevent timing dependencies and resource conflicts caused by trying to share the same memory resources between different operations running in non-deterministic sequences.The trouble with shared mutable state is that if your input state depends on some other instruction’s output state, and any sort of concurrency arises, it creates race conditions. If you change the order in which instructions are called, it can alter the results. Mix in any sort of non-determinism in sequencing, and the result is chaos: unpredictable, unprovable, seemingly random application state. Sometimes it works. Sometimes it doesn’t. Not only does encapsulation provide a solution to these problems, but it provides protective layering to our AppState and information and processes we don't want the user to have access to.
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
200
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```

```