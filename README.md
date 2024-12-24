# Qr_code_generator_using_Python

This is a Python script to generate a QR code for a given URL, using the qrcode library and Pillow for image processing.

Requirements

Python 3.x

The following Python libraries must be installed:

qrcode

Pillow

Installation

To install the required libraries, run:

pip install qrcode[pil] Pillow

Explanation

Version: Determines the size of the QR code (1 is the smallest).

Error Correction: Allows the QR code to be partially damaged but still readable. ERROR_CORRECT_H provides a high level of error correction.

Box Size: Sets the pixel size of each box in the QR code.

Border: Specifies the width of the border (minimum is 4).

Fill Color: The color of the QR code.

Back Color: The background color of the QR code.

Output

The script generates a QR code with the specified URL and saves it as E_learning.png in the current working directory. The QR code has red foreground and white background colors.
