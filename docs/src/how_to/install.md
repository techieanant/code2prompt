# Installation

## Binary releases

Download the latest binary for your OS from [Releases](https://github.com/mufeedvh/code2prompt/releases/latest).

## Source build

Requires:

- [Git](https://git-scm.org/downloads), [Rust](https://rust-lang.org/tools/install) and Cargo.

```sh
git clone https://github.com/mufeedvh/code2prompt.git
cd code2prompt/
cargo build --release
```

# cargo

installs from the [`crates.io`](https://crates.io) registry.

```sh
cargo install code2prompt
```

For unpublished builds:

```sh
cargo install --git https://github.com/mufeedvh/code2prompt
```

## AUR

`code2prompt` is available in the [`AUR`](https://aur.archlinux.org/packages?O=0&K=code2prompt). Install it via any AUR helpers.

```sh
paru/yay -S code2prompt
```

## Nix

If you are on nix, You can use `nix-env` or `profile` to install.

```sh
# without flakes:
nix-env -iA nixpkgs.code2prompt
# with flakes:
nix profile install nixpkgs#code2prompt
```
