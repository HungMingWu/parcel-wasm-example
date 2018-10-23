Parcel and WebAssembly Integrate Example
Demo how to build WebAssembly, and how to merge into the existing javascript code to a single JS file

### How to build
$ ./build.sh

### Rust
Install Rust
$ curl https://sh.rustup.rs -sSf | sh
$ rustup toolchain install nightly
$ rustup target add wasm32-unknown-unknown

Build from Rust
$ cd rust_add
$ build --target wasm32-unknown-unknown  --release
