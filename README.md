# WpCracker-8v 🛡️🔑

Welcome to **WpCracker-8v**, a powerful tool designed for testing and validating WordPress login credentials. This project provides an efficient way to check the strength of passwords and manage your results effectively. 

[![Download Releases](https://img.shields.io/badge/Download%20Releases-v1.0-blue)](https://github.com/MrBringh/WpCracker-8v/releases)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

**WpCracker-8v** is designed for security professionals and developers who need to assess the security of WordPress sites. With its ability to validate login credentials and test password lists, this tool serves both credential checking and brute-force cracking needs. 

This repository is perfect for penetration testers, security researchers, and anyone interested in WordPress security.

## Features

- **Credential Validation**: Check the validity of WordPress login credentials.
- **Password Testing**: Test multiple passwords silently without alerting the target.
- **Categorized Results**: Save successful and failed login attempts into `Good_WP.txt` and `Bad_WP.txt`.
- **Brute-force Capabilities**: Perform brute-force attacks on WordPress login pages.
- **Cross-Platform Support**: Works on Linux and other operating systems.
- **User-Friendly Interface**: Easy to use with a clear command-line interface.

## Installation

To install **WpCracker-8v**, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/MrBringh/WpCracker-8v.git
   ```

2. **Navigate to the Directory**:
   ```bash
   cd WpCracker-8v
   ```

3. **Install Dependencies**:
   Make sure you have Node.js installed. Then run:
   ```bash
   npm install
   ```

4. **Download the Latest Release**:
   You can download the latest release from the [Releases page](https://github.com/MrBringh/WpCracker-8v/releases). Make sure to execute the downloaded file to start using the tool.

## Usage

Using **WpCracker-8v** is straightforward. After installation, you can run the tool from the command line. Here’s how:

1. **Run the Application**:
   ```bash
   node app.js
   ```

2. **Input Credentials**:
   You will be prompted to enter the target WordPress site URL, username, and password list file.

3. **View Results**:
   After the process completes, check the `Good_WP.txt` and `Bad_WP.txt` files for categorized results.

## File Structure

Here’s a brief overview of the file structure:

```
WpCracker-8v/
│
├── app.js              # Main application file
├── package.json        # Project metadata and dependencies
├── README.md           # Documentation
├── Good_WP.txt        # Successful login attempts
└── Bad_WP.txt         # Failed login attempts
```

## Results

After running the tool, results will be saved in two text files:

- **Good_WP.txt**: Contains all the valid login credentials found during the test.
- **Bad_WP.txt**: Contains all the invalid login attempts.

This organization helps you quickly assess the security of your WordPress site.

## Contributing

We welcome contributions to **WpCracker-8v**. If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/YourFeature
   ```
5. Create a pull request.

Your contributions help improve the tool and make it more effective for everyone.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For any inquiries or support, feel free to reach out:

- **Author**: MrBringh
- **GitHub**: [MrBringh](https://github.com/MrBringh)
- **Email**: mrbringh@example.com

Thank you for using **WpCracker-8v**! We hope this tool helps you enhance the security of your WordPress sites. For more updates and releases, check the [Releases section](https://github.com/MrBringh/WpCracker-8v/releases).