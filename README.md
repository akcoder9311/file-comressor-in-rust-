# The File Compressor
This Rust project is a command-line application that compresses files using the `flate2` crate. It reads an input file, compresses it using `Gzip`, and writes the compressed data to an output file.

## Features
1. `Compress Files`: Compress any file using Gzip compression.
2. `Time Measurement`: Records and displays the time taken to compress the file.
3. `CLI Usage`: Simple command-line interface for easy usage.

## Prerequisites
Before running this project, ensure you have the following installed:
`Rust`

## Getting Started
### Clone the Repository
`git clone`: https://github.com/yourusername/rust-file-compressor.git

`cd rust-file-compressor`

### Build the Project
#### Build the project using Cargo: 
cargo build --release


### Running the Application
#### Run the application with the required arguments:
cargo run --release -- <input_file> <compressed_file>

`For example`:
cargo run --release -- input.txt compressed.txt 


### Contributing
Contributions are welcome! Please create a pull request with a clear description of your changes.

### License
This project is licensed under the MIT License. See the LICENSE file for details.
