# Lattice-Based Encryption Rust Project

This Rust project implements lattice-based encryption functionalities using matrix operations. It provides modules for encrypting and decrypting CSV data files with specified encryption keys.

Presentation Link: [https://docs.google.com/presentation/d/1DrshoYlo5VLek2xoPk5Fx1VUsJ6SxCxzVOjUzn1B0v4/edit?usp=sharing]
## Table of Contents

- [Modules](#modules)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Setup](#setup)
- [File Structure](#file-structure)

## Modules

The project consists of the following Rust modules:

- **lattice_decrypt**: Module for decrypting encrypted CSV files.
- **lattice_encrypt**: Module for encrypting CSV files using lattice-based encryption techniques.
- **encrypted**: Additional module for encrypted file operations.
- **decrypted**: Additional module for decrypted file operations.
- **verification**: Module for verification and validation of lattice encryption.

## Usage

To use this project, follow these steps:

1. **Clone Repository**:

2. **Install Rust**:
Ensure you have Rust installed on your system.

3. **Build and Run**:

4. **Encrypt CSV**:
Use the provided HTTP endpoint `/encrypt` to upload and encrypt a CSV file.

5. **Decrypt CSV**:
Use the HTTP endpoint `/decrypt` to upload and decrypt an encrypted CSV file.

## Dependencies

- **nalgebra**: Linear algebra library for matrix operations.
- **csv**: CSV file parsing library for Rust.
- **actix-web**: Web framework for asynchronous Rust applications.
- **actix-multipart**: Support for multipart form data handling.

## Setup

1. **Environment Setup**:
Ensure Rust and Cargo are installed.

2. **Clone Repository**:
Clone this repository to your local machine.

3. **Install Dependencies**:
Update and install required dependencies using Cargo:

4. **Run Application**:
Build and run the application locally:
