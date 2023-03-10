---
id: mio0y
title: π Live Snippets
file_version: 1.1.1
app_version: 1.1.0
---

## What are Live Snippets?

Live Snippets are pieces of code from your repository, embedded into your documents.

**Example for a Live Snippet:**

<br/>

The snippet below defines a function called "$on" that binds an event listener to a target element and takes four arguments. The function uses the addEventListener method of the target object to bind the event listener and passes.<br/>
_(see this purple dotted underline above? this is a code-coupling suggestion. learn more about it_ [emhere](https://docs.swimm.io/Features/code-coupling-suggestions)_)_
<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### π examples/vanilla-es6/src/helpers.js
```javascript
19     export function $on(target, type, callback, capture) {
20     	target.addEventListener(type, callback, !!capture);
21     }
```

<br/>

<br/>

## π Try it yourself!

Go to edit mode - if youβre not already in edit mode.

Type πππ "/snippet" below, followed by an Enter.

<br/>

## The benefits of Swimm Live Snippets

β Using parts of your code in your documents does most of the work for you.<br/>
Let the code explain what it does, and you explain the underlying assumptions and connections between different code areas.

β Swimmβs Auto-sync algorithm takes are of tracking the code in the document,<br/>
making sure the document is always up to date as the code evolves.

<br/>

<div align="center"><img src="https://firebasestorage.googleapis.com/v0/b/swimm-dev-content/o/repositories%2FZ2l0aHViJTNBJTNBdG9kbyUzQSUzQVlvc3NpU2FhZGk%3D%2Fae177e2d-281a-4bd1-9e32-467d9be302d1.png?alt=media&token=73f3a52a-6c04-4b1b-a9c1-3e852f14bb7f" style="width:'100%'"/></div>

<br/>

<br/>

## Live snippets and the IDE

The illustration above shows how you can find snippets in your **Swimm IDE extension.**

<br/>

This file was generated by Swimm. [Click here to view it in the app](https://swimm-web-app.web.app/repos/Z2l0aHViJTNBJTNBdG9kbyUzQSUzQVlvc3NpU2FhZGk=/docs/mio0y).
