<h1 align="center">Welcome to One Dionys - PDF Generation Utilities! 👋 </h1>

<p align="center">A utility for generating PDF documents from dynamic content in web applications, such as reports or invoices. 💖 </p>

<p align="center">
<img src="https://img.shields.io/github/contributors/onedionys/onedionys-pdf-generation-utilities?style=flat-square">
<img src="https://img.shields.io/github/issues/onedionys/onedionys-pdf-generation-utilities?style=flat-square">
<img src="https://img.shields.io/github/stars/onedionys/onedionys-pdf-generation-utilities?style=flat-square"> 
<img src="https://img.shields.io/github/forks/onedionys/onedionys-pdf-generation-utilities?style=flat-square">
<img src="https://img.shields.io/github/last-commit/onedionys/onedionys-pdf-generation-utilities.svg?style=flat-square">
<img src="https://img.shields.io/github/languages/code-size/onedionys/onedionys-pdf-generation-utilities?style=flat-square">
<img src="https://img.shields.io/github/license/onedionys/onedionys-pdf-generation-utilities?style=flat-square">
</p>

## 💾 Requirements

* `Web Browser` - Can be used as an emulator to build applications. Example [Chrome, Firefox, Safari & Opera].
* `Internet` - Because many use CDN and to make it easier to find solutions to all problems.

## 🎯 How To Use

#### Example Syntax

```javascript
const { generatePDF } = require('pdf-generation-utilities');

const data = {
    // Your data to be included in the PDF
};

generatePDF(data)
    .then(pdfPath => {
        console.log('PDF generated:', pdfPath);
    })
    .catch(error => {
        console.error('Error generating PDF:', error);
    });
```

#### Explanation

* This package exports a single function generatePDF(data) which takes an object data as input and returns a promise. The generatePDF function generates a PDF document based on the provided data and returns the path to the generated PDF file.

#### Return Value

* The generatePDF function returns a promise that resolves with the path to the generated PDF file.

## 📆 Release Date

* v1.0.0 : 18 March 2024

## 🧑 Author

* Facebook : <a href="https://www.facebook.com/theonedionys"> Oned Ionys</a>
* Instagram : <a href="https://www.instagram.com/onedionys/"> @onedionys</a>
* Twitter : <a href="https://twitter.com/onedionys"> @onedionys</a>
* LinkedIn :  <a href="https://www.linkedin.com/in/onedionys/"> @onedionys</a>

## 📝 License

* Copyright © 2024 One Dionys
* **One Dionys - PDF Generation Utilities is an open source project licensed under the MIT license**

## ☕️ Suppport & Donation

Love One Dionys - PDF Generation Utilities? Support this project by donating or sharing with others in need.

<a href="https://www.buymeacoffee.com/onedionys"><img src="https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black"/> </a>

**Made with ❤️ One Dionys**
