# 📲 QR Code Generator

This project is a simple QR code generator that takes a URL input from the user and generates a QR code image file (`qr_img.png`) and a text file (`URL.txt`) containing the URL.

## Prerequisites

- Node.js v20.14.0 or higher
- npm (Node Package Manager)

## 🚀 Setup

### Install `nvm` (Node Version Manager)

If you don't have `nvm` installed, you can install it by running the following command:

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
After installing nvm, add it to your shell profile and reload your shell:

```bash
source ~/.bashrc  # or ~/.zshrc, ~/.bash_profile, etc.
📦 Install Node.js
Use nvm to install and use Node.js v20.14.0:

```bash
nvm install 20.14.0
nvm use 20.14.0
nvm alias default 20.14.0
🔄 Clone the Repository
Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/qrcode-generator.git
cd qrcode-generator
🔧 Install Dependencies
Install the required npm packages:

```bash
npm install
💡 Usage
Run the application:

```bash
npm start
You will be prompted to enter a URL. After entering the URL, the application will generate a QR code image file (qr_img.png) and a text file (URL.txt) containing the URL.

🌟 Example
Run the application:

```bash
npm start
Enter your URL when prompted:

```bash
? Type in your URL: https://example.com
The application will generate qr_img.png and URL.txt in the project directory.

📂 Files
app.js: The main script file.
qr_img.png: The generated QR code image (created after running the application).
URL.txt: The text file containing the entered URL (created after running the application).
🤝 Contributing
If you would like to contribute to this project, please fork the repository and create a pull request with your changes.

📝 License
This project is licensed under the ISC License.

👨‍💻 Author
Joseph

📌 Additional Information
If you encounter any issues or have questions, feel free to open an issue on the GitHub repository.
