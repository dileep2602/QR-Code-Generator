
# QR Code Generator

This project is a simple and efficient QR code generator built using Node.js and Express.js. It utilizes the Inquirer and qr-image packages to create QR codes based on user input from the command line.

## Features

- **User-Friendly CLI:** Uses Inquirer for an interactive command-line interface to gather input from the user.
- **QR Code Generation:** Leverages the qr-image package to generate QR codes from the user-provided data.
- **Express.js Integration:** Provides a web interface via Express.js to generate and display QR codes.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/dileep2602/QR-Code-Generator.git
   ```
2. Navigate to the project directory:
   ```bash
   cd qr-code-generator
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```

## Usage

### Command Line Interface

1. Start the Express.js server:
   ```bash
   node index.js
   ```
2. Enter the data you want to encode and generate the QR code.

## Dependencies

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [Inquirer](https://www.npmjs.com/package/inquirer)
- [qr-image](https://www.npmjs.com/package/qr-image)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License.

---