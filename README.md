# Steganography
# 🕵️‍♂️ Hiding Text in Image Using Steganography

This project demonstrates how to hide and retrieve secret text messages inside images using the **Least Significant Bit (LSB)** technique of steganography.

> ✅ Original and output images look the same to the human eye, but one contains a hidden message.

---

## 📌 Features

- Encode any text message inside a PNG image
- Decode and retrieve hidden messages from images
- Uses Python and PIL (Pillow) for image manipulation
- Simple, lightweight, and effective

---

## 📷 How It Works

- Converts each character of your message into binary (8 bits)
- Replaces the **Least Significant Bit** of each pixel’s RGB values with the binary data
- Adds a unique binary delimiter to signal the end of the message
- The modified image looks exactly the same but holds hidden information

---

## 🧪 Requirements

- Python 3.6 or higher
- Install dependencies:

```bash
pip install pillo

screenshots :orginal image
![sample_image](https://github.com/user-attachments/assets/5d0c70b8-22cd-4f35-ad6c-2916d00dcdb8)
encoded image
![encoded_image](https://github.com/user-attachments/assets/ec6adc97-6869-406d-b611-810ab6c84afc)



