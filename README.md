# 🖼️ SteganoCrypt - Image Steganography Tool

SteganoCrypt is a powerful image steganography tool that allows you to securely hide and extract secret messages within images using **Least Significant Bit (LSB) encoding**. It ensures safe message embedding and retrieval using a **passcode for protection**.

---

## 🚀 Features

✅ **Encrypt Messages** – Hide secret text inside an image using LSB encoding.  
✅ **Decrypt Messages** – Extract hidden messages with a passcode.  
✅ **Passcode Protection** – Ensures only authorized users can retrieve messages.  
✅ **Simple & Fast** – Uses OpenCV and standard Python libraries for efficiency.  
✅ **No External Dependencies** – Works without NumPy for lightweight execution.  

---

## 📦 Installation

Ensure you have **Python 3** and **Git** installed, then install OpenCV:

```sh
pip install opencv-python
```

Clone the repository:

```sh
git clone https://github.com/Akshai-M/Secure-Data-Hiding-In-Images-Using-Steganography.git
cd Secure-Data-Hiding-In-Images-Using-Steganography
```

---

## ⚡ Usage

### 🔒 Encrypt a Message into an Image

Run the encryption script:

```sh
python3 encryption.py
```

Follow these steps:
1. Enter the image path (supports **.png, .jpg, .jpeg** formats).
2. Enter the output file name (must be **.png** to preserve data).
3. Provide the **secret message** to hide.
4. Set a **passcode** for additional security.
5. The encrypted image is saved successfully!

### 🔑 Decrypt a Hidden Message

Run the decryption script:

```sh
python3 decryption.py
```

Follow these steps:
1. Enter the **path of the encrypted image**.
2. Enter the **correct passcode**.
3. The hidden **secret message** is revealed!

---

## 🔧 Requirements

- **Python 3.x**
- **OpenCV (opencv-python)**

---

## ⚠️ Notes & Warnings

- If you are using **Linux or macOS**, use `python3 encryption.py` / `python3 decryption.py`.
- The **output image must be in PNG format** to preserve the hidden message.
- If the **passcode is incorrect**, the message **cannot be retrieved**.
- **Large messages require high-resolution images** to store the data properly.

---

## 📜 License

This project is **open-source** and free to use under the [MIT License](LICENSE).

---

## 🤝 Contributing

We welcome contributions! If you'd like to improve the project:
- Fork the repository
- Create a new branch
- Submit a pull request

Feel free to **star ⭐ the repository** if you find it useful!

---

## 📩 Contact

For any issues or suggestions, reach out via GitHub Issues.

Happy Steganography! 🖼️🔐
