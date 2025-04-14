# QR Code Generator - Python

A simple Python script to generate QR codes from URLs or text.

## Description

This project demonstrates how to create a QR code using Python with the `qrcode` library. The script generates a QR code for a LinkedIn profile URL and saves it as a PNG image file.

## Prerequisites

- Python 3.x installed on your system
- pip (Python package installer)

## Installation

1. First, install the required `qrcode` package using pip:

```bash
pip install qrcode[pil]
```

The `[pil]` extra ensures you also have the Python Imaging Library (Pillow) installed, which is needed for image generation.

## How to Run the Code

1. Clone this repository or download the `code_1.py` file
2. Open a terminal/command prompt in the directory containing the file
3. Run the script with Python:

```bash
python code_1.py
```

4. After running, you'll find a new file named `ashishhrd.png` in the same directory containing the generated QR code.

## Customizing the QR Code

To generate a QR code for a different URL or text:
1. Open `code_1.py` in a text editor
2. Replace the URL in the `qrcode.make()` function with your desired text or URL
3. Save the file and run it again

Example:
```python
image = qrcode.make("Your custom text or URL here")
```

## Output

The script will generate a PNG image file containing the QR code. You can scan this QR code with any smartphone QR code reader to access the encoded information.

## Dependencies

- [qrcode](https://github.com/lincolnloop/python-qrcode) - QR Code generator library
- [Pillow](https://python-pillow.org/) - Python Imaging Library (handles image creation)
