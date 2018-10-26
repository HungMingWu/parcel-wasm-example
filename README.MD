Parcel and WebAssembly Integrate Example
Demo how to build WebAssembly, and how to merge into the existing javascript code to a single JS file

### How to build

``` bash
$ npm install parcel-bundler --global
$ ./build.sh
```

### Rust
Install Rust
``` bash
$ curl https://sh.rustup.rs -sSf | sh
$ rustup toolchain install nightly
$ rustup target add wasm32-unknown-unknown
```

Build wasm from Rust

```
$ cd rust_add
$ cargo build --target wasm32-unknown-unknown  --release
```
