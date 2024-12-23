# Dueling Voting System

## Overview

A decentralized and secure voting system built on the **Internet Computer Protocol (ICP)**. This project ensures transparent, verifiable, and tamper-proof voting through the use of **Zero-Knowledge Proofs (ZKP)**, enabling privacy and data integrity for every vote cast. The entire system is developed using **Rust**, leveraging its performance and safety features.

## Key Features
- **Zero-Knowledge Proofs (ZKP)**: Each vote is validated using a Zero-Knowledge Proof, ensuring its authenticity without revealing any voter information.
- **Decentralized & Scalable**: Deployed on the Internet Computer (ICP), leveraging its decentralized, secure infrastructure for maximum scalability and availability.
- **Stable Storage**: Uses **stable memory** (via `StableBTreeMap` and `VirtualMemory`) to store vote data persistently and immutably.
- **Flexible Voting Mechanism**: Allows for vote casting, updating, querying, and vote counting.
- **Query Functionality**: Retrieve votes by ID, candidate, or voter ID for full transparency.

## Unique Functions
- **Secure Voting**: Voters can cast and modify their votes securely with the help of **ZKPs**.
- **Vote Tracking**: Easily track the vote count for any candidate and retrieve specific votes by ID or voter.
- **ZKP Validation**: Efficiently validate the ZKP for each vote to ensure its authenticity without compromising voter privacy.
- **ICP-native**: Runs natively on the ICP network, ensuring maximum decentralization and security while enabling easy scaling.

##  How It Works
- **Add Vote**: A user can add a vote along with the ZKP proof for the selected candidate.
- **Modify Vote**: Voters can modify their votes if necessary, ensuring flexibility and user control.
- **Retrieve Vote**: Users can query votes by vote ID or encrypted voter ID.
- **Vote Count**: The system can tally votes for any candidate, offering a transparent and real-time vote count.
- **Zero-Knowledge Proof Verification**: Votes are accompanied by ZKPs that ensure their validity without exposing sensitive information.

##  Technical Details
- **Language**: Written in **Rust** using the `ic-cdk` framework. Rust provides performance and memory safety, making it an ideal choice for blockchain development on ICP.
- **Storage**: Leverages **StableBTreeMap** for persistent, stable data storage on ICP’s decentralized network.
- **Web Interface**: Can be queried via API for front-end integration or tested directly with `dfx` commands.
- **High Compatibility**: Fully compatible with ICP’s decentralized environment for robust and secure operation.


