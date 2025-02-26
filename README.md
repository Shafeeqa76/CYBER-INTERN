# CYBER-INTERN
# **LSB Image Steganography**  

## **📌 Project Overview**  
This project implements **image steganography** using the **Least Significant Bit (LSB) technique** in Python. It allows users to securely hide a secret message within an image and later extract it without altering the image's appearance.  

## **🔍 Features**  
✅ Hide secret messages inside images without visible changes.  
✅ Retrieve hidden messages from encoded images.  
✅ Supports file upload/download in **Google Colab**.  
✅ Uses **LSB technique** for efficient and lossless data hiding.  
✅ Simple and easy-to-use interface.  

## **🛠 Technologies Used**  
- **Python** – Core programming language  
- **Pillow (PIL)** – For image processing  
- **OS module** – To handle file operations  
- **Google Colab** – For file upload and download support  

## **📂 How to Use**  
### **1️⃣ Encoding a Message (Hiding a Message in an Image)**  
1. Run the script in **Google Colab**.  
2. Choose **option 1 (Encode)** when prompted.  
3. Upload an image file (BMP is recommended).  
4. Enter the secret message you want to hide.  
5. The encoded image will be saved and available for download.  

### **2️⃣ Decoding a Message (Retrieving the Hidden Message)**  
1. Choose **option 2 (Decode)** when prompted.  
2. Upload the previously encoded image.  
3. The hidden message will be extracted and displayed.  

## **🚀 Getting Started**  
1. Clone this repository:  
   ```bash
   git clone https://github.com/Shafeeqa76/lsb-image-steganography.git
   cd lsb-image-steganography
   ```
2. Open and run the script in **Google Colab**.  
3. Follow the on-screen instructions to encode/decode messages.  

## **📌 Example Usage**  
- **Input Image:** `cover_image.bmp`  
- **Secret Message:** `"Hello, this is a hidden message!"`  
- **Output Image:** `encoded_image.png`  
- **Decoded Message:** `"Hello, this is a hidden message!"`  

## **📖 Applications**  
🔹 Secure communication and privacy protection  
🔹 Digital watermarking for copyright protection  
🔹 Cybersecurity and forensic analysis  
🔹 Covert messaging and data hiding  

## **🎯 Future Enhancements**  
- Add **encryption** for better security.  
- Support for **more image formats**.  
- GUI version for **better user experience**.  

