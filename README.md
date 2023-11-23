# kanagawa-login-rs

A very simple but reactive login page based on the [kanagawa.nvim](https://github.com/rebelot/kanagawa.nvim) theme, built with Rust on the blazingly-fast Leptos framework.

## Run

Install the Rust Nightly toolchain with `rustup`:

`rustup toolchain install nightly`

Add `wasm` to your build targets:

`rustup target add wasm32-unknown-unknown`

Ensure that `trunk` and `cargo-leptos` is installed:

`cargo install --locked trunk` (use the `--locked` flag to ensure no errors)

`cargo install cargo-leptos`

Clone the repository, `cd` into the directory, then run:

`cargo leptos watch`

Enjoy nerd
