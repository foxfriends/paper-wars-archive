[rustup]: https://rustup.rs/
[Node.js]: https://nodejs.org/en/

# Paper Wars (official name TBD)

Build your own strategy game with Paper Wars. Design worlds complete with units, maps and even
unique behaviours.

## Does this work?

No.

## Developing

To start developing Paper Wars, clone this repository and the submodules.

```bash
git clone git@github.com:oinkiguana/paper-wars --recursive
```

Note that you will probably want to `git checkout master` on each of the submodules before developing,
as the refs may not have been updated in this repository.

### Rust projects

Install Rust with [rustup]().

### Web projects

Install latest [Node.js]() and NPM.

Install Rust as above, and then install `wasm-pack`:

```bash
cargo install wasm-pack
```
