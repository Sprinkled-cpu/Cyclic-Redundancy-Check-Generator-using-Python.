# 🔄 Cyclic Redundancy Check (CRC) in Python

This Kaggle notebook demonstrates how to implement and simulate the Cyclic Redundancy Check (CRC) algorithm in Python. CRC is a widely used error-detecting code commonly employed in digital networks and storage devices to detect accidental changes to raw data.

## 📘 What is CRC?

Cyclic Redundancy Check is a technique used to detect errors in digital data. It works by performing polynomial division on the data and appending a checksum (CRC bits) to the message. At the receiver's end, the same division is performed to verify data integrity.

## 📂 Notebook Contents

- Introduction to CRC and its applications
- Python implementation of CRC encoding and decoding
- Simulation of data transmission with and without errors
- Visualization of CRC detection capability

## 🧪 How It Works

1. **Encoding**: The sender appends CRC bits to the original data using a generator polynomial.
2. **Transmission**: The encoded data is sent over a simulated channel.
3. **Decoding**: The receiver checks the remainder after division to detect errors.

## 🧠 Key Functions

```python
def xor(a, b):
    # Performs XOR between two binary strings
    ...

def mod2div(dividend, divisor):
    # Performs modulo-2 division
    ...

def encodeData(data, key):
    # Encodes data using CRC
    ...

def decodeData(data, key):
    # Verifies data integrity
    ...
