# metalog

Explicit metadata for logs

<img src="https://deniskolodin.com/logo-dev.png" height="32px" align="right" />

To support the project, subscribe to the [Knowledge.Dev](https://knowledge.dev/) interactive book for practicing Rust.

## Description

This crate is an extension to add values to logs and visualize them.

A log record of an application is a text line with details like the following:

```rust
log::info!("The application started");
```

```rust
log::info!("The application started | key=value");
```

```rust
metalog!("The application started", key = value);
```
