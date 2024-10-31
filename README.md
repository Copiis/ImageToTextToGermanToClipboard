# Image Text Reader and Translator

This Tampermonkey userscript allows users to extract text from images on a webpage by right-clicking the image. The extracted text is then translated into English and copied to the clipboard for easy use.

## Features

- **Right-click to extract text**: Simply right-click on any image to initiate the text extraction process.
- **Text recognition**: Utilizes Tesseract.js for Optical Character Recognition (OCR) to accurately read text from images.
- **Translation**: Automatically translates the recognized text into English using Google Translate.
- **Clipboard functionality**: Copies the translated text to your clipboard for quick access.

## Installation

1. **Install Tampermonkey**: Make sure you have the Tampermonkey extension installed in your browser.
   
   - [Chrome Web Store](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmipfmgdfohlll?hl=en)
   - [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)
   - [Microsoft Edge Add-ons](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/dhdgffkkebhmipfmgdfohlll?hl=en)

2. **Create a new script**: Open the Tampermonkey dashboard and click on "Create a new script".

3. **Paste the code**: Copy the code from the script provided in this repository and paste it into the Tampermonkey script editor.

4. **Save the script**: Click on the "File" menu and then "Save".

## Usage

- Navigate to a webpage containing images.
- Right-click on any image to extract and translate the text from it.
- An alert will notify you once the translated text is copied to your clipboard.

## Dependencies

- **Tesseract.js**: This script relies on Tesseract.js for optical character recognition.
- **GM_xmlhttpRequest**: Used for making cross-origin requests to Google Translate.

## License

This project is licensed under the MIT License. Feel free to modify and use the script as per your needs.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have suggestions or improvements.

## Acknowledgments

- [Tesseract.js](https://github.com/naptha/tesseract.js) for providing the OCR functionality.
- [Google Translate](https://translate.google.com/) for translation services.
