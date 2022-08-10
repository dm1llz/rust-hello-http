# The Rust Language Book HTTP Server

This is an implementation of an HTTP server following the final chapter in [The Rust Programming Language](https://doc.rust-lang.org/book/)

The goal is to continue to build out the server to learn and implement common Rust practices, idioms and tools. 
The goal will be to implement the suggestions in the chapter itself and other expected functions of an HTTP server.

- [x] Warn attributes
  - missing_debug_implementations
  - rust_2018_idioms
  - missing_docs
- [x] Set up and run clippy
- [x] Add more documentation to ThreadPool and its public methods.
- [ ] Add tests of the library’s functionality.
- [ ] Change calls to unwrap to more robust error handling.
- [ ] Use ThreadPool to perform some task other than serving web requests.
- [ ] Find a thread pool crate on crates.io and implement a similar web server using the crate instead. Then compare its API and robustness to the thread pool we implemented. 