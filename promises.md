# Promises

### When callbacks can't cut it.

##### Guide
MDN - Using promises  
[https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Using_promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Using_promises)

##### Interesting Articles
- "We have a problem with promises" by Nolan Lawson  
[https://pouchdb.com/2015/05/18/we-have-a-problem-with-promises.html](https://pouchdb.com/2015/05/18/we-have-a-problem-with-promises.html)

##### Thoughts
- Personally, I'm a fan of using promises instead of callbacks.  I think part of it is due to not having to deal with the callback mountain or having to handle the `err` part of the callback every time.  (Instead opting for the "if anything fails throughout this series of promises" catch statement.  Well, when I don't need to clean up after specific parts.)
