# A Rust Site Engine

A Rust Site Engine, or `arse`, is static site generator written in Rust. It seeks to provide a simple
and flexible base for serving sites using:

* [Tera](https://tera.netlify.app/) for templates
* [pulldown-cmark](https://crates.io/crates/pulldown-cmark) for CommonMark rendering
* [routerify](https://crates.io/crates/routerify) to serve the site

## Binary

* Run an existing site given the path to its config TOML: `arse run config.toml`
* Create and run a new site from user input: `arse new`

## Library

`arse` can be used as a library to extend functionality as the user sees fit.

Documentation can be found [here](https://docs.rs/arse/).

### License

Licensed under either of

 * Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
 * MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be dual licensed as above, without any
additional terms or conditions.
