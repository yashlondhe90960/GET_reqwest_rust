# GET_reqwest_rust

This is a Rust project that demonstrates how to perform a GET request using the reqwest crate.

## Prerequisites

Before running this project, ensure that the following prerequisites are met:

- Rust is installed on your system. If not, you can install Rust from the official website: https://www.rust-lang.org/tools/install

## Clone the Repository

To get started, clone this repository to your local machine using the following command:

```shell
git clone https://github.com/yashlondhe90960/GET_reqwest_rust.git
```
## Project Structure

The project contains the following files:

- `src/main.rs`: The main Rust source file that contains the code to perform the GET request.
- `Cargo.toml`: The Cargo manifest file that manages project dependencies.

## Build and Run

1. Change to the project directory:

   ```shell
   cd GET_reqwest_rust
   ```

2. Build the project using Cargo:

   ```shell
   cargo build
   ```
This command will download and compile the necessary dependencies and create the executable binary in the target/debug directory.

3. Run the project:

   ```shell
   cargo run
   ```
This command will compile and execute the Rust code. You should see the output in the console.

## Usage
By default, the project performs a GET request to "http://httpbin.org/get" and displays the response. You can modify the URL or customize the code in the src/main.rs file according to your requirements.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to submit a pull request or open an issue.
