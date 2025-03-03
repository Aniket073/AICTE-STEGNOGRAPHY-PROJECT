Steganography Project - Hiding Message in an Image

Overview

This project demonstrates how to hide a secret message inside an image using steganography techniques with Python and OpenCV. The encryption program encodes a message into an image, and the decryption program retrieves the hidden message using a passcode.

Features

Encrypt a message into an image using pixel manipulation.

Decrypt the message from the image with the correct passcode.

Uses OpenCV for image processing.

Simple command-line interface.

Technologies Used

Python

OpenCV

NumPy

String Encoding

Prerequisites

Ensure you have the following installed on your system:

Python 3

OpenCV (pip install opencv-python)

Installation & Setup


 Steganography-Project

Install dependencies:

pip install opencv-python

Place an image (mypic.jpg) in the project folder.

Usage

Encryption

Run the encryption script to embed a message into an image:

python encryption.py

Enter the secret message and a passcode.

The encrypted image will be saved as encryptedImage.jpg.

The passcode will be stored in password.txt.

Decryption

Run the decryption script to retrieve the hidden message:

python decryption.py

Enter the correct passcode to reveal the message.

Example

Encryption:

Enter secret message: Hello, World!
Enter a passcode: 1234
Encryption completed! Encrypted image saved.

Decryption:

Enter passcode for Decryption: 1234
Decryption message: Hello, World!

Troubleshooting

If password.txt or encryptedImage.jpg is missing, ensure you have run encryption.py first.

Verify that the passcode entered during decryption matches the one used during encryption.




