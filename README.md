Blockchain Simulation

Overview

This project is a basic blockchain simulation in Python. It mimics the core features of a blockchain, including block structure, hashing, proof-of-work, and chain validation. The program demonstrates how blocks are linked, validated, and how tampering is detected.

Features

Block Structure:

Each block contains:

Block index

Timestamp of creation

List of transactions

Hash of the previous block

Current block hash

Nonce for proof-of-work

Hashing:

Uses the SHA-256 algorithm to generate block hashes.

Proof-of-Work:

Ensures that block creation is computationally intensive by requiring hashes to start with a specified number of leading zeros.

Blockchain Class:

Manages the chain of blocks.

Validates the integrity of the chain.

Tampering Detection:

Demonstrates how tampering with a block invalidates the entire chain.

Prerequisites

Python 3.7+

Setup and Execution

1. Clone the Repository

git clone [https://github.com/dhanushgit72/blockchain-simulation.git](https://github.com/dhanushgit72/blockchain_simulation)
cd blockchain-simulation

2. Install Dependencies

This project has no external dependencies, but ensure Python 3.7+ is installed.

3. Run the Simulation

python b

4. Output

The program will mine blocks, display the blockchain, and validate its integrity.

Tampering with the blockchain will demonstrate how the validation detects inconsistencies.

Code Structure

blockchain-simulation/
|-- blockchain_simulation.py  # Main simulation script
|-- README.md                 # Project documentation

Docker Setup

To run the project in a Dockerized environment, follow these steps:

1. Build the Docker Image

docker build -t blockchain-simulation .

2. Run the Container

docker run --rm blockchain-simulation



