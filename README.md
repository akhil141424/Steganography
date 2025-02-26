# Steganography: Hiding messages in images
Steganography is Cyber security technique used to hide secret messages within images. 
The current project allows users to encrypt message inside an image and retrieve it later using a password-based authentication system.

# Features
Message Encryprion: Hides a secret message within an image by modifying the pixel values of the image.

Password protection: Ensures that only authorized users can access the secret message by decrypting the image.

Simple and Lightweight: Uses OpenCV for image processing and works with minimal dependencies.

# Working
1. The user provides an image and a secret message.
2. The script modifies the pixel values of the image and embed the message within the image.
3. The encrypted image is saved as EncryptedImage.jpg.
4. The user can access the decrypted message by entering the correct password.

# Technologies used
1. Python
2. OpenCV
3. OS Module

# Tips 
Ensure that the system contains the CV2 python module installed.

# Usage:
Run the script and follow the prompts to encrypt or decrypt messages in images.
