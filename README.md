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

### Web projects

Not sure yet, these don't exist properly.
