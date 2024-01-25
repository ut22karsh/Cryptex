# Cryptex

# Encryption and Decryption Tool (AES)

This is a simple Python script for encrypting and decrypting files using the AES (Advanced Encryption Standard) algorithm. The script provides a command-line interface and includes options for encrypting individual files, decrypting files, and performing bulk encryption and decryption in a directory.

## Features

- AES encryption and decryption with key-based authentication
- Options to encrypt and decrypt individual files
- Bulk encryption and decryption for all files in a directory
- Password-based authentication for added security
- Progress bars using the tqdm library

## Prerequisites

- Python 3.x
- Required Python libraries (`Crypto`, `tqdm`, `termcolor`)

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/encryption-tool.git
   ```

2. Navigate to the project directory:

   ```bash
   cd encryption-tool
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the script:

   ```bash
   python script.py
   ```

## Password Setup

- If the `password.txt.enc` file is not found, the script will guide you through the setup process, allowing you to either generate a random password or manually set one.

## Caution

- This script is designed for educational purposes and should be used with caution, especially when dealing with sensitive data.
- Ensure that the password is stored securely, and consider additional security measures for sensitive applications.

## License

This project is licensed under the [MIT License](LICENSE).

## Author

- Utkarsh Pandey
- linkedin.com/in/ut22karsh

