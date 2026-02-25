# StegSecure: Encrypted Data Hiding in Images

A hybrid steganography system built in Python using XOR encryption, LSB embedding, and pixel tweaking to securely hide text within images—all implemented in a Jupyter Notebook.

---

## 🧠 About the Project

### 🔍 Inspiration  
In today’s digital world, protecting sensitive information is more critical than ever. Traditional encryption secures the message but not its existence. This project explores **steganography**, which conceals messages within images, combining it with **XOR encryption** for added security.

---

## ⚙️ How It Works

1. The user inputs a secret message and a key.
2. The message is encrypted using repeating-key **XOR** logic.
3. The encrypted binary data is embedded into the **Least Significant Bits (LSB)** of an image.
4. Small pixel tweaks are added to avoid detection.
5. The hidden message is extracted and decrypted using the same key.

---

## 🛠️ Built With

Python 3.7+, OpenCV, NumPy, Matplotlib, Jupyter Notebook

---

## 📄 How to Run

1. **Clone the Repository**
```bash
git clone https://github.com/hemamalini5/Steganography.git
cd Steganography
