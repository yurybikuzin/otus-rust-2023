# otus-rust-2023

Курс "Rust Developer" на сайте [otus.ru](https://otus.ru)

## About Cargo

Run `cargo` inside `src/rust`:

```
cd src/rust
cargo check -p fizz_buzz
```

## Tools, can be installed by `cargo install`

[A curated list of command-line utilities written in Rust](https://gist.github.com/sts10/daadbc2f403bdffad1b6d33aff016c0a)

## Most advanced `cargo clippy` call

cargo clippy --all --all-features --tests -- -D warnings


## Q&A

### А можно `clippy` фичу закрыть для всего файла? 

```
#![allow(clippy::too_many_arguments)] 
```
