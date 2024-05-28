# RDN Ransomware System

## Description

RDN Ransomware System is a simulated ransomware program designed for educational purposes only. This system demonstrates the mechanics of file encryption and decryption typically employed by ransomware. **It is intended solely for learning and awareness. Do not use this tool for malicious activities.**

## Features

- **File Encryption**: Encrypts user files to simulate a ransomware attack.
- **File Decryption**: Provides a method to decrypt the files once the ransom is 'paid.'
- **Educational Use**: We disclaim any responsibility for any damage or misuse of this software. It is provided strictly for educational purposes only. By using this software, you agree to use it responsibly and understand that it should not be used for any illegal or malicious activities. The creators cannot be held liable for any consequences arising from the use or misuse of this software.

## Disclaimer

This project is strictly for educational purposes. The authors are not responsible for any misuse of this software. Use this tool responsibly and ethically.

## Installation Guide

### Prerequisites

- Visual Studio Community Edition
- .NET Framework

### Step-by-Step Installation

1. **Clone the Repository**

    ```sh
    git clone https://github.com/yourusername/RDN-Ransomware-System.git
    cd RDN-Ransomware-System
    ```

2. **Download Visual Studio Community**

    Download and install [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/). During installation, select the ".NET desktop development" workload.

3. **Download Source Code**

    - Download the encrypter code:
        - Go to the provided GitHub link.
        - Click on "Code" and select "Download ZIP".
        - Extract the ZIP file to a safe folder (not your desktop).

    - Download the decrypter code:
        - Repeat the above steps for the decrypter code.

4. **Open the Project in Visual Studio**

    - Navigate to the encrypter's folder.
    - Open the solution file (`Encrypter.sln`) in Visual Studio.
    - Unlock the file if necessary by right-clicking, selecting "Properties", and then "Unblock".

5. **Build and Run the Encrypter**

    - Clean and build the solution in Visual Studio.
    - Navigate to `bin/Debug` to find the executable.
    - Run the executable to start the encryption process.

6. **Decrypting Files**

    - Open the decrypter's solution file (`Decrypter.sln`) in Visual Studio.
    - Ensure the password matches the encrypter's password.
    - Clean and build the solution.
    - Run the decrypter executable from `bin/Debug` to decrypt the files.

## Usage

1. **Encrypting Files**

    Run the encrypter executable. It will encrypt files in the specified directories and append a custom extension to indicate encryption.

2. **Decrypting Files**

    Run the decrypter executable with the correct password to decrypt the files and restore them to their original state.

## Project Structure

- `Encrypter/`: Contains the encrypter source code and executable.
- `Decrypter/`: Contains the decrypter source code and executable.
- `README.md`: Project description and installation guide.

## Contributing

We welcome contributions to enhance the educational value of this project. Please submit pull requests with detailed descriptions of your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
This project is based on an educational ransomware demonstration originally created by Josh Madakor.
