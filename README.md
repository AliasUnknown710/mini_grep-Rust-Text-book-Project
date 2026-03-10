# Minigrep

A simple command-line tool for searching text in files, written in Rust.

## Installation

Ensure you have Rust installed on your system. You can install Rust from [rustup.rs](https://rustup.rs/).

Clone the repository:

```bash
git clone https://github.com/yourusername/minigrep.git
cd minigrep
```

Build the project:

```bash
cargo build --release
```

## Usage

Run the tool with a search query and a filename:

```bash
./target/release/minigrep [query] [filename]
```

For example:

```bash
./target/release/minigrep the poem.txt
```

This will search for the word "the" in `poem.txt` and print the matching lines.

## Contributing

Feel free to submit issues and pull requests.

## License

This project is licensed under the MIT License.