# Mini Blockchain in Python

This is a simple and unique blockchain implementation in Python.  
It demonstrates the core concepts of blockchain: blocks, hashing, proof-of-work (mining), and chain validation.

## Features
- Genesis block creation
- Block mining with proof-of-work
- Adding new blocks with transaction data
- Validation of blockchain integrity

## How to Run
1. Ensure you have Python 3 installed.
2. Clone or download this repository.
3. Run the following command:
   ```bash
   python blockchain.py
   ```

## Expected Output
- It will mine 2 blocks with difficulty `2`.
- You will see block hashes and mined confirmation.
- At the end, it will confirm whether the blockchain is valid.
- Finally, it will print all block details.

## Example Output
```
Mining block 1...
Block mined: 00a93f7a...
Mining block 2...
Block mined: 00b12ac4...
Blockchain valid? True
{'index': 0, 'previous_hash': '0', 'timestamp': ..., 'data': 'Genesis Block', 'nonce': 0, 'hash': '...'}
{'index': 1, 'previous_hash': '...', 'timestamp': ..., 'data': {'amount': 10}, 'nonce': ..., 'hash': '...'}
{'index': 2, 'previous_hash': '...', 'timestamp': ..., 'data': {'amount': 20}, 'nonce': ..., 'hash': '...'}
```
