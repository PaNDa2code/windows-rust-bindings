# Windows Rust Bindings

These are Rust bindings generated for `windows.h` and `winternal.h` (from mingw) using `bindgen`. I made them for personal usage.

- Bindings for `windows.h`: This includes definitions for Windows API functions and data types commonly used for application development on the Windows platform.
- Bindings for `winternal.h`: This includes definitions for internal Windows structures and functions, providing access to low-level system details and functionality.

## Usage

To use these bindings in your Rust project, simply add this repository as a dependency in your `Cargo.toml` file:

```toml
[dependencies]
windows_bindings = { git = "https://github.com/panda2code/windows-rust-bindings" }
```
