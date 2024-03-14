# Partisia Blockchain Example Contracts

This repository contains example smart contracts for the Partisia Blockchain, showcasing various use cases and functionalities.

Official documentation:
https://partisiablockchain.gitlab.io/documentation/smart-contracts/compile-and-deploy-contracts.html

## Setup and Installation on Ubuntu

This guide assumes you're using an Ubuntu system. Adjustments may be needed for other Linux distributions.

### Prerequisites

- Git
- Rust and Cargo
- Node.js and npm (if interacting with contracts via JavaScript)
- Docker (optional, for containerized environments)

### Installing Rust and Cargo

1. Install Rust and Cargo using rustup:

   ```sh
   curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
   ```

   Follow the on-screen instructions to complete the installation.

2. Configure your current shell to access cargo commands:

   ```sh
   source $HOME/.cargo/env
   ```

### Clone the Repository

Clone this repository to your local machine:

```sh
git clone https://github.com/oktaykurt/partisia-blockchain-example-contracts.git
cd partisia-blockchain-example-contracts
```

### Build the Contracts

To compile the smart contracts, run:

```sh
cargo build --release
```

### Running Tests

If your project includes tests, describe how to run them:

```sh
cargo test
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with your improvements.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
