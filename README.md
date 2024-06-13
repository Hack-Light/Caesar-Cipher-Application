# Caesar Cipher Text Encryption/Decryption Application

This application allows users to encrypt plaintext using a Caesar Cipher and decrypt ciphertext back to plaintext, given the correct key. It is built using HTML, CSS, and JavaScript and provides a simple, interactive interface for users to perform encryption and decryption.

## Features

- Encrypt plaintext using a key to generate ciphertext.
- Decrypt ciphertext using the correct key to reveal the original plaintext.
- Copy the encrypted or decrypted text to the clipboard.
- Responsive design for use on different devices.

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge, etc.)

### Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/Hack-Light/Caesar-Cipher-Application.git
   ```
2. Navigate to the project directory:
   ```bash
   cd caesar-cipher-app
   ```
3. Open `index.html` in your web browser to view and use the application.

### Hosting

The application can be hosted using GitHub Pages, Vercel, or any other static site hosting service.

## Usage

1. **Encryption**

   - Open the application in your web browser.
   - Ensure the "Encrypt" section is active.
   - Enter the plaintext you wish to encrypt in the "Text to Encrypt" input field.
   - Enter the shift key (a number) in the "Shift By" input field.
   - Click the "Submit" button.
   - The encrypted text will be displayed below.
   - Click the "Copy" button to copy the encrypted text to your clipboard.

2. **Decryption**
   - Open the application in your web browser.
   - Switch to the "Decrypt" section by clicking the toggle.
   - Enter the ciphertext you wish to decrypt in the "Text to Decrypt" input field.
   - Enter the shift key (a number) used during encryption in the "Shift By" input field.
   - Click the "Submit" button.
   - The decrypted text will be displayed below.
   - Click the "Copy" button to copy the decrypted text to your clipboard.

### Example

- **Encrypting the text "HELLO" with a key of 3:**

  - Text to Encrypt: `HELLO`
  - Shift By: `3`
  - Encrypted Text: `KHOOR`

- **Decrypting the text "KHOOR" with a key of 3:**
  - Text to Decrypt: `KHOOR`
  - Shift By: `3`
  - Decrypted Text: `HELLO`

## Project Structure

```
caesar-cipher-app/
│
├── index.html         # The main HTML file
├── style.css          # CSS file for styling
└── README.md          # This README file
```

## Development

If you wish to contribute to the project or modify it for your needs, you can follow the standard Git workflow:

1. Fork the repository.
2. Clone your fork:
   ```bash
   git clone https://github.com/Hack-Light/Caesar-Cipher-Application.git
   ```
3. Create a new branch for your feature or bugfix:
   ```bash
   git checkout -b feature-name
   ```
4. Make your changes and commit them:
   ```bash
   git add .
   git commit -m "Description of your changes"
   ```
5. Push your changes to your fork:
   ```bash
   git push origin feature-name
   ```
6. Create a pull request from your branch to the main repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- UI: [UI Design](https://codepen.io/ig_design/pen/KKVQpVP)
