# Lab 8 - WebSockets

## Question 1: What do you see in the browser? When you open another tab and perform a click/drag action, what happens?
The browser loads a black canvas with a bunny in the top-left corner. It can be clicked and dragged across the canvas, with its position synchronized between multiple clients.

## Question 2: What are some of the differences between TypeScript and JavaScript?
The main difference is that TypeScript is statically typed, while JavaScript is not. JavaScript is a subset of TypeScript, and during compilation, TypeScript emits JavaScript after type checking.

## Question 3: Why is a web application bundler (Parcel, Webpack, Rollup, etc.) useful for modern web projects? What are some features that ParcelJS provides?
Web application bundlers like Parcel are useful for bundling JavaScript modules into a single file. Bundling with ParcelJS will reduce network traffic by only requiring a single file fetch, and will ensure dependencies are loaded in the correct order.

## Question 4: What are the different values for the readyState a WebSocket can be in? Briefly describe what each state means. (Hint: check out the Mozilla WebSocket API)
The readyState property can have four different values:
* 0 CONNECTING: A socket exists but has no connection yet.
* 1 OPEN: The socket has a connection and is ready to communicate.
* 2 CLOSING: The socket connection is closing.
* 3 CLOSED: The socket connection has been closed or failed to open.

## Question 5: What's the link to your github repo?
https://github.com/dlallan/nodejs-ws-lab
