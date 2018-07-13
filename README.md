# Learning Reactive Programing

## Topics

* [The introduction to Reactive Programming you've been missing](https://gist.github.com/staltz/868e7e9bc2a7b8c1f754)
* [Cycle.js](https://cycle.js.org/)

## RxJS

### Why RxJS

> Concurrency

* User input
* Event handling
* Sending request

### What is RxJS

> It's Reactive eXtensions library for JavaScript

ReactiveX is an API for asynchronous programing with observable streams

> Streams are collections of events

* User input events
* Caching data
* API calls

### Observables

|       | Singular       | Plural            |
| ----- | -------------- | ----------------- |
| Sync  | Value          | Interable<Value>  |
| Async | Promise<Value> | Observable<Value> |

Creating Observables

```javascript
return new Observable(observer => {
  observer.next('Hello World');
  observer.complete();
});
```

### RxJS Operators

* transform
* filter
* combine
* alter
