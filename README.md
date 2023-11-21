Signature Pad

This HTML file provides a simple web-based signature pad where users can draw their signatures. The signature can be saved as a PNG file with a customizable filename.
Features

    Canvas Signature Pad:
    The main feature is a canvas-based signature pad where users can draw their signatures.

    Save as PNG:
    Users can save their signatures as PNG files. The saved file is named based on the user's input (last name) and includes a watermark with the current date and time.

    Clear Signature:
    Users can clear the signature pad if they want to start over.

Usage

    Open the HTML file in a web browser.

    Draw your signature on the canvas.

    Click the "Save as PNG" button to save the signature as a PNG file.

    Optionally, click the "Clear" button to clear the signature pad and start over.

Additional Information

    The signature pad uses the Signature Pad library to handle drawing on the canvas.

    The saved PNG file includes a watermark with the current date and time. Users are prompted to enter their last name, which is used to generate the filename.

    The filename of the saved PNG file is displayed below the signature pad.

    An image element (signature-image) is hidden by default and is used to display the saved signature image.

File Structure

    index.html: The main HTML file containing the signature pad and associated JavaScript code.
    signature_pad.min.js: The Signature Pad library for handling canvas-based signatures.

Credits

    Signature Pad Library

Author

Jason deNobel

License
This project is licensed under the MIT License.

Feel free to contribute and enhance the features! If you encounter any issues, please report them in the issue tracker.
