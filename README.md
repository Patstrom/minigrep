# minigrep

Chapter 12 of the Rust language book is an exercise to write a small version of grep.

This is the code.

# Usage

```bash
cargo run <pattern> <filename>
```

## Example

```bash
cargo run the poem.txt
```

## Case insensitive search

Set the environment variable `CASE_INSENSITIVE` to any value.

```bash
CASE_INSENSITIVE=1 cargo run the poem.txt
```
