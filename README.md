# URL to QR Code Generator
This project is a simple Node.js application that converts a user-provided URL into a QR code image. It uses the following npm packages:
- inquirer for getting user input from the command line.
- qr-image for generating a QR code based on the URL.
- The Node.js fs module to save the URL in a text file.

Features
1. Prompt the user to enter a URL using inquirer.
2. Generate a QR code image of the provided URL using qr-image.
3. Save the user input (URL) to a .txt file using the fs module.

Prerequisites
Make sure you have Node.js installed on your system. You can check this by running:
`node -v`

Getting Started
Installation
1. Clone this repository:
`git clone https://github.com/yourusername/url-to-qr-code-generator.git`

2. Navigate to the project directory:
`cd url-to-qr-code-generator`

3. Install the necessary dependencies:
`npm install`

Usage

1. Run the script:
`node index.js`

3. Enter the URL when prompted. The application will:
- Generate a QR code and save it as qr_image.png in the project directory.
- Save the URL in a text file named url_text.txt.
Example:
```bash
node index.js
Enter the URL: https://example.com
```

After entering the URL, you should see the following files created in your project directory:
qr_image.png - The QR code image generated from the URL.
url_text.txt - A text file containing the URL.

Dependencies
inquirer
qr-image
fs (File System) (Native Node.js module)

License
This project is open-source and available under the MIT License.

Acknowledgments
Thanks to the developers of inquirer and qr-image for their packages.
