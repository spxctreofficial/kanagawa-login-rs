<p align="center">
<h1 align="center">kanagawa-login-rs</h1>
</p>

<p align="center">A very simple but reactive login page based on the built with Rust on the blazingly-fast Leptos framework.
</p>

<p align="center">Colorscheme based on <a href="https://github.com/rebelot/kanagawa.nvim">kanagawa.nvim</a>.</p>

## Run

Install the Rust Nightly toolchain with `rustup`:

```bash
rustup toolchain install nightly
```

Add `wasm` to your build targets:

```bash
rustup target add wasm32-unknown-unknown
```

Ensure that `trunk` and `cargo-leptos` is installed:

```bash
cargo install --locked trunk
```

(use the `--locked` flag to ensure no errors)

```bash
cargo install cargo-leptos
```

Clone the repository, `cd` into the directory, then run:

```bash
cargo leptos watch
```

Enjoy nerd
