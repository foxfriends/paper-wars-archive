[Rust]: https://www.rust-lang.org/
[rustup]: https://rustup.rs/
[Node.js]: https://nodejs.org/en/
[nvm]: https://github.com/nvm-sh/nvm

# Paper Wars (official name TBD)

Build your own strategy game with Paper Wars. Design worlds complete with units, maps and even
unique behaviours.

## Does this work?

No.

## Status

This project is currently on hold, as I develop [Lumber](https://github.com/foxfriends/lumber)
which I hope can be used as the scripting language to implement the components of this game.
I hope to successfully build [Root](https://github.com/foxfriends/root) using Lumber before
continuing here, as that is a smaller scale at which to try out the language and work out the
kinks.

## Developing

To start developing Paper Wars, clone this repository and the submodules.

```bash
git clone git@github.com:foxfriends/paper-wars --recursive
```

You will probably want to `git checkout master` on each of the submodules before developing,
so that your commits end up on a branch.

```bash
git submodule foreach git checkout master
```

### Rust projects

The Rust projects use the standard Rust setup, with Cargo.

Due to various version compatibility issues, a lot of the crates in use here are just pointing at 
the `master` branch of their respective repositories or forks, rather than an actual release. Expect
builds to randomly fail sometimes when these dependencies get updated.

Setup steps:
*   Install Rust with [rustup][]. 
*   Use `cargo` to build/run the project.
    *   `cargo build`
    *   `cargo run`

### Web projects

The web projects are actually also using Rust, and compiled for web using WASM. Therefore, both
Rust and JavaScript environments must be set up for this to work.

*   Install Rust with [rustup][].
*   Install [Node.js][] (optionally with [nvm][] or your favourite version manager).
*   Install [wasm-pack][]: `cargo install wasm-pack`.
*   Install NPM dependencies: `npm install`
*   Use `npm` to build/run the project.
    *   `npm run build`
    *   `npm run watch`
    *   `npm start
