# rust-on-nixos

A minimal "Hello world" to start hacking with Rust on NixOS.

## How to use

Requirements:
- Nix with extra experimental features `nix-command` ([docs](https://nixos.wiki/wiki/Nix_command)) and `flakes` ([docs](https://nixos.wiki/wiki/Flakes))

1. Fork and clone this repository.
2. Run
   ```console
   nix develop
   ```
3. Run
   ```console
   cargo run
   ```

This should print "Hello world".

Now, your turn to hack!

If you want to use an IDE (e.g. VSCode), don't forget to run them from the Nix shell.

## Why?

Nix is nice and all, but sometimes you just want the vanilla experience.

## References

This repo is basically a ripoff of the Nix Wiki page: https://nixos.wiki/wiki/Rust
