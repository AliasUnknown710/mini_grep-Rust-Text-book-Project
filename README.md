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

On Unix/Linux:

```bash
./target/release/minigrep [query] [filename]
```

On Windows:

```powershell
.\target\release\minigrep.exe [query] [filename]
```

For example:

On Unix/Linux:

```bash
./target/release/minigrep the poem.txt
```

On Windows:

```powershell
.\target\release\minigrep.exe the poem.txt
```

This will search for the word "the" in `poem.txt` and print the matching lines.

To perform a case-insensitive search, set the `IGNORE_CASE` environment variable:

On Unix/Linux:

```bash
IGNORE_CASE=1 ./target/release/minigrep the poem.txt
```

On Windows (PowerShell):

```powershell
$env:IGNORE_CASE = "1"; .\target\release\minigrep.exe the poem.txt
```

On Windows (CMD):

```cmd
set IGNORE_CASE=1 && target\release\minigrep.exe the poem.txt
```

## Contributing

Feel free to submit issues and pull requests.

## License

MIT License

Copyright (c) 2026 Your Name

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.