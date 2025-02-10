# MiniBlockChain

# MiniBlockchain: A Simple Java Blockchain Implementation

This project implements a minimal blockchain in Java, focusing on core concepts like cryptographic linking, block structure, and basic Proof-of-Work. It's designed to be easy to understand and explore the fundamentals of blockchain technology.

## What is it?

MiniBlockchain is a simplified version of a blockchain, demonstrating how blocks are chained together cryptographically. Each block contains data (like a transaction), a timestamp, and a hash of the previous block. This chaining and hashing are what make blockchains secure and tamper-proof.

## Features

* **Block Structure:**  Each block neatly packages transaction data, a timestamp (so you know when the transaction happened), and a cryptographic hash.  This hash is like a digital fingerprint for the block.

* **Cryptographic Linking:** The magic of blockchain! Each block includes the hash of the previous block. This creates a chain of blocks, and if you try to change one block, it messes up all the subsequent blocks.

* **Chain Verification:** You can check the integrity of the blockchain.  The code will go through the chain and make sure all the hashes line up correctly.

## How it Works

Imagine a chain of linked boxes. Each box (block) contains a message (data), the time you wrote the message (timestamp), and a special code (hash) that's unique to that message.  Importantly, each box contains the special code from the box before it.

If you try to change the message in one box, the special code for that box changes.  This change then affects the special code in the next box, and so on down the line.  So, everyone can easily see if someone has tried to tamper with any of the messages.

MiniBlockChain implements this idea in Java.  It's a simplified version, but it captures the essence of how blockchains work.

