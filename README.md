# ZK-Proof-Hash-Preimage

## Overview

RustZKHashDemo is a Rust implementation showcasing the use of Zero-Knowledge Proofs (ZKPs) for the verification of a hash preimage without revealing the preimage itself. This project demonstrates the power and flexibility of zk-SNARKs, a form of ZKPs, in creating privacy-preserving cryptographic protocols. It's designed to serve as an educational tool and a foundation for more complex ZKP applications, highlighting the potential of Rust in cryptographic implementations.

## Features

- **Zero-Knowledge Proof of Hash Preimage**: Demonstrates proving knowledge of a hash preimage without disclosing any information about the preimage.
- **Use of zk-SNARKs**: Leverages zk-SNARKs to create compact and efficient proofs.
- **Rust Implementation**: Utilizes Rust's performance and safety features to implement cryptographic protocols.

## Getting Started

### Prerequisites

- Rust: Make sure you have Rust installed on your machine. If not, follow the instructions [here](https://www.rust-lang.org/tools/install).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rosemary-crypto/ZK-Proof-Hash-Preimage.git

2. Navigate to the project directory:
   cd ZK-Proof-Hash-Preimage

3. Build the project
   cargo build --release

### Running the demonstration
- To run the proof generation and veification process, use
    cargo run

### How It Works
The project is structured around the implementation of a Zero-Knowledge Proof system using zk-SNARKs in Rust. It follows three main phases:

1. Setup Phase: Generates a proving key and a verification key based on a common reference string.
2. Proving Phase: Computes a proof that the prover knows the preimage of a specific hash without revealing the preimage.
3. Verification Phase: Checks the proof against the hash and the verification key to confirm that the prover knows the preimage without learning what it is.

## Acknowledgments

- **libsnark**: A C++ library for zk-SNARKs.
- **ZoKrates**: A toolbox for zk-SNARKs on Ethereum.
- **Rust Programming Language**

## Contact

- Rosemary Koikara - [rosekoikara@gmail.com](mailto:rosekoikara@gmail.com)
