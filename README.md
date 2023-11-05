# Node.js QR Code Generator

This Node.js application allows you to generate QR codes for URLs and store the entered URL in text format. It makes use of built-in Node.js modules like `inquirer`, `qr-image`, and `fs` to create and save QR codes.

## Features

- **QR Code Generation:** Easily generate QR codes for URLs.
- **URL Storage:** The entered URL is stored in a text file for reference.
- **User-Friendly CLI:** The application uses `inquirer` to prompt users for the URL.

## Getting Started

Follow these steps to get started with the QR Code Generator:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Sarthakbante07/Node.js-QR_Code-Generator.git

2. **Navigate to the Project Directory:**
  ```bash
  cd Node.js-QR-Code-Generator
```

3. **Install Dependencies:**
 ```bash
npm install
```

4. **Run the Application:**
```bash
node qr-code-generator.js
```

Follow the Prompts: The application will prompt you to enter the URL for which you want to generate a QR code. After entering the URL, it will generate the QR code and save the URL in a text file.

Find the QR Code: The generated QR code will be saved in the project directory as qr-code.png.

## Dependencies
This project relies on the following Node.js modules:

inquirer: For interactive command-line prompts.
qr-image: For generating QR codes.
fs: For file system operations.
Make sure to install these dependencies using npm install before running the application.

## Contributing
If you would like to contribute to this project, please feel free to submit a pull request or open an issue. Your contributions are welcome.

## License
This project is licensed under the [MIT License].

If you have any questions or need further assistance, don't hesitate to reach out. Happy QR code generating!

