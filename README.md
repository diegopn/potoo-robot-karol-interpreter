<p align="center">
  <img src="https://diegopn.github.io/potoo-site/src/assets/images/language-interpreter-icon.svg?v=1c651ca7" alt="Potoo IDE language interpreter icon" width="120" />
</p>

<h1 align="center">Robot Karol Interpreter Scaffold</h1>

<p align="center">A minimal Rust scaffold concerning Robot Karol, a German educational programming environment.</p>

<p align="center">
  <a href="https://diegopn.github.io/potoo-site/manual/robot-karol/">Website</a> ·
  <a href="https://diegopn.github.io/potoo-site/manual/robot-karol/">User manual</a>
</p>

<p align="center">
  <a href="https://www.rust-lang.org/"><img alt="Rust" src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white"></a>
  <a href="https://doc.rust-lang.org/cargo/"><img alt="Cargo" src="https://img.shields.io/badge/Cargo-DEA584?style=for-the-badge&logo=rust&logoColor=white"></a>
</p>

This Rust package is part of the Potoo IDE ecosystem and is separate from the desktop interface. Compatibility with the IDE has not been implemented or verified.

Robot Karol is a German educational programming environment distinct from Karel the Robot.

## Status

This candidate is under evaluation. The repository contains only a minimal Rust crate skeleton. It does not implement a language, notation, or environment, and provides no runnable CLI or language tests. No prebuilt release is available.

## Build the scaffold

Install Rust 1.93 or later. From the repository root, run:

```sh
cargo fmt --all -- --check
cargo check --locked
```

## Support

If this project is useful to you, you can support its continued development:

<p align="left">
  <a href="https://github.com/sponsors/diegopn"><img alt="Become a sponsor" src="https://img.shields.io/badge/Become_a_sponsor-EA4AAA?style=for-the-badge&logo=githubsponsors&logoColor=white"></a>
</p>

## Project policies

- [Code of conduct](CODE_OF_CONDUCT.md)
- [Contributing](CONTRIBUTING.md)
- [Security policy](SECURITY.md)
- [GPL-3.0-or-later license](LICENSE)
