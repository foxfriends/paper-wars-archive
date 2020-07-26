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
git clone git@github.com:foxfriends/paper-wars --recursive
```

You will probably want to `git checkout master` on each of the submodules before developing,
so that your commits end up on a branch.

### Rust projects

Install Rust with [rustup](). Due to various version compatibility issues, a lot of the crates in use here are
just pointing at the `master` branch of their respective repositories or forks, rather than an actual release.
We also have to use the nightly Rust release, as the server is using Rocket. That is supposed to change
soon, so let's keep an eye on that.

Once you have installed Rust, you can install the nightly release and set it to be used:

```sh
rustup install nightly
rustup override set nightly
```

### Web projects

Not sure yet, these don't exist properly.
