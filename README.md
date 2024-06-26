# Image-Encryption-Tool-using-Pixel-Manipulation
This is a simple Python program that performs image encryption and decryption using pixel manipulation. The program allows users to encrypt and decrypt images by applying a basic mathematical operation to each pixel.
## Table of Contents
1. Description
2. Requirements
3. Installation
4. Usage
5. Examples
6. License
## Description
The Image Encryption Tool uses a simple method to encrypt and decrypt images. The program shifts the value of each pixel by a specified key, effectively encrypting the image. Decryption is achieved by reversing this operation using the same key.
## Requirements
1. Python 3.x
2. Pillow library

## Examples
### Encrypting an Image
```bash
Would you like to (e)ncrypt or (d)ecrypt an image? (e/d): e
Enter the path to the image: example_image.png
Enter the encryption key (integer value): 42
Image encrypted and saved as 'encrypted_image.png'
```
### Decrypting an Image
```bash
Would you like to (e)ncrypt or (d)ecrypt an image? (e/d): d
Enter the path to the image: encrypted_image.png
Enter the encryption key (integer value): 42
Image decrypted and saved as 'decrypted_image.png'
```

