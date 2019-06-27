# Rust notes

Install Rust using ```rustup``` - [instructions](https://www.rust-lang.org/tools/install).

You'll need to add this to your ```~/.bash_profile``` file:

```
export PATH = $PATH:~/.cargo/bin
```

Restart your shell and see if it works

```
rustc --version
rustc 1.35.0 (3c235d560 2019-05-20)

rustup --version
rustup 1.18.3 (435397f48 2019-05-22)
```

## Usage
```
git clone https://github.com/geocolumbus/rust-notes.git
cd rust-notes
rustc main.rs
./main
```

## Reference

* [The Rust Reference](https://doc.rust-lang.org/reference/index.html)
* [The Rust Programming Langauge](https://doc.rust-lang.org/book/)
