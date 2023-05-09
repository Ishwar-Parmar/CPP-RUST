# CPP-RUST
Install Rust and C++ compiler.
Version:
 Cargo : 1.69.0
 Rustc : 1.69.0
 Rustup : 1.26.0
 G++ : 11.3.0

Install autocxx - 'cargo install autocxx'
add "[dependencies]
autocxx = "0.25.0"
cxx = "1.0"

[build-dependencies]
autocxx-build = "0.25.0"
miette = { version = "5", features = ["fancy"] } # optional but gives nicer error messages!"
   - to toml file

Then run commands: 'cargo build' then 'cargo run'.
