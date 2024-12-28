# QR Code Generator

**Author:** Satyam Kumar Singh

This project is a simple QR code generator built using Node.js and Express. It allows users to enter a URL or text and generate a corresponding QR code image.

**Features**

* Generate QR codes from URLs or text.
* User-friendly interface with a text input field and a generate button.
* Displays the generated QR code image on a separate page.
* Option to return to the main page after generating a QR code.
* Basic error handling for QR code generation.

**Getting Started**

1. **Prerequisites**
    * Node.js and npm (or yarn) installed on your system.

2. **Clone the repository**

    ```bash
    git clone [https://github.com/satyamx33/QR-code-generator.git](https://github.com/satyamx33/QR-code-generator.git) 
    ```

3. **Install dependencies**

    ```bash
    cd qr-code-generator
    npm install
    ```

4. **Run the application**

    ```bash
    npm start
    ```

    This will start the server and the application will be accessible on http://localhost:3000/ by default.

**Usage**

1. Open http://localhost:3000/ in your web browser.
2. Enter a URL or text in the text area.
3. Click the "Generate QR Code" button.
4. The generated QR code image will be displayed on a new page.
5. Click the "Back" button to return to the main page.

**Code Structure**

* **index.js:** The main server file that configures Express, routes, and templating.
* **index.ejs:** The EJS template for the main page with a form to enter text or URL.
* **scan.ejs:** The EJS template for the page that displays the generated QR code image.
* **public:** This directory contains static files like CSS and potentially JavaScript files if needed in the future.

**Technologies Used**

* Node.js: JavaScript runtime environment for server-side development.
* Express: A popular Node.js web framework for building web applications.
* EJS: A templating engine for Node.js that allows embedding dynamic content within HTML code.
* qrcode: A Node.js library for generating QR code images.

**License**

 MIT License

**Contributing**

Contributions are welcome! Please feel free to fork this repository and submit pull requests for any improvements or new features.

This README file provides a basic overview of the QR Code Generator project. You can further enhance it by adding screenshots, more detailed instructions, and any other relevant information.
