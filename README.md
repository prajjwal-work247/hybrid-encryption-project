
# hybrid-encryption-project
Hybrid Secure File Transfer using AES and XChaCha20

# Hybrid Encryption Project
This project implements a hybrid encryption scheme using AES (for file stream encryption) and XChaCha20 (for wrapping the AES key).

## Objectives
- Encrypt files using AES-256 in streaming mode (AES-GCM or AES-CTR).
- Wrap the AES key securely using XChaCha20 (or ChaCha20-Poly1305 as an alternative).
- Evaluate correctness, performance, and basic security behavior.

## Folder Structure
- `aes_stream_encrypt.py` – AES module
- `xchacha20_wrap.py` – key wrapping module
- `integrate.py` – combined flow
- `tests/` – contains test files and logs
- `report/` – contains documentation and final report drafts

## Setup
Install dependencies:
```bash
pip install pycryptodome pynacl```## To Do
- Implement AES encryption/decryption
- Implement XChaCha20 key wrapping
- Integrate and test
- Write report and performance results

