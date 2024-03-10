# QR Code Generator
### QR Code Generator

This is a simple QR code generator project implemented using JavaScript, Node.js, and npm packages like "inquirer" and "qr-image".

## Description

This project allows users to generate QR codes for any text input provided by the user. It utilizes the "qr-image" npm package to generate QR codes and "inquirer" package for a user-friendly command-line interface (CLI) to input text.

## Dependencies

To run this project, you need to have the following dependencies installed:

- Node.js: Make sure you have Node.js installed on your system. You can download and install Node.js from [here](https://nodejs.org/).



## Installation

To install the project dependencies, run the following command in your terminal:

```bash
npm install

```

This will install all the required dependencies listed in the `package.json` file.

If you're planning to run this project using ECMAScript modules (ESM), you need to ensure that the type field in your package.json file is set to module. You can change it manually or run the following command:

```bash
npm init -y && npm config set type module
```
This command initializes a new package.json file with default values and sets the type field to module.

## Usage

After installing the dependencies, you can run the QR code generator using the following command:
```bash
node index.js
```
This will start the CLI interface where you can enter the text for which you want to generate the QR code.

## Dependencies Used

- **inquirer**: Used for creating a user-friendly CLI interface to accept user input.
- **qr-image**: Utilized for generating QR codes based on the text input provided by the user.

## Contributing

Contributions are welcome 🤍! If you have any ideas, suggestions, or bug fixes, feel free to open an issue or create a pull request on GitHub.

**Author: [Jayesh Minigi](https://github.com/jayeshminigi)**
## License

This project is licensed under the [MIT License](LICENSE).




![preview img](/preview.png)