# PRODIGY_CS_02
A Python script that encrypts and decrypts images using XOR operations and pixel manipulation.

Simple Image Encryption Tool is a Python script that encrypts and decrypts images using XOR operations and pixel manipulation. It allows users to secure images with a secret key, ensuring that only those with the correct key can decrypt and restore the original image. The tool supports multiple image formats and guarantees lossless encryption by saving outputs in PNG format. With its lightweight design and simple command-line usage, it provides an easy and efficient way to protect image data.  

Usage 

To encrypt an image:  

python image.py encrypt input.jpg encrypted.png 12345

- `input.jpg` → The original image file to be encrypted  
- `encrypted.png` → The output file where the encrypted image will be saved  
- `12345` → The encryption key (a numeric value that scrambles the image)  

To decrypt an image:  

python image.py decrypt encrypted.png decrypted.png 12345

- `encrypted.png` → The encrypted image file  
- `decrypted.png` → The output file where the decrypted image will be saved  
- `12345` → The same encryption key used earlier (must match exactly for correct decryption)  

If the wrong key is used during decryption, the image will not be restored properly.  
