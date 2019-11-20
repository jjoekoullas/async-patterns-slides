# Why do I care?
You asked for it, you tell me.

# Overview
1. Definition
    
    "of or requiring a form of computer control timing protocol in which a **specific operation begins upon receipt of an indication (signal) that the preceding operation has been completed.**"
2. Callbacks
    >setTimeout(() => alert('ding'), 0) 
3. Promises
    > var p = new Promise((resolve, reject) => setTimeout(resolve, 0))
    >
    > p.then(() => alert('ding'))
4. Async/await
    > async function() {
    >
    > var p = new Promise((resolve, reject) => setTimeout(resolve(7), 0))
    >
    > var r = await p;
    >
    > }
5. Callback hell
6. Handling failure