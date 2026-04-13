# client-side-cloud-functions-suite
A client-side cloud functions suite, build with WASM .

The goal is to create a library with usefull WASM functions that are usable in but more performant than javascript.

Load the WASM functions you want and use them in your client application.

It doesn't even have to be limited for use within javascript, they could also be used in python and other languages that can invoke wasm. 
Like https://wasmtime.dev/

Things like document / image / audio / video manipulation.
Client side file conversions. The data doesn't even have to go through the backend.

With WASM, web client applications can do a lot more things that native applications can do. And still be performant. 

This library can for example make use of WIT (Wasm Interface Type).
https://component-model.bytecodealliance.org/design/wit.html
https://component-model.bytecodealliance.org/design/wit-example.html
Which could be a way of calling other wasm functions in your wasm function.


