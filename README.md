# QR Code Generator and Decoder

A Python-based web application that generates a QR code from a URL or text and also decodes an uploaded QR code image to display the stored information.

## Problem Statement

Manually typing long URLs or sharing text can be time-consuming, and users may make mistakes while entering long links. Many existing applications support either QR code generation or QR code decoding, but not both in one place. Therefore, this project provides a single web-based application for generating and decoding QR codes.

## Project Description

This project allows users to enter a URL or text, such as a LinkedIn profile link, and instantly generate a scannable QR code. It also allows users to upload an existing QR code image and decode it to display the hidden URL or text.

The application was developed and tested in Google Colab using Gradio. A Streamlit web application was created for the frontend, and the backend was deployed using Render.

## Features

- Generate QR code from a URL or text
- Display the generated QR code
- Decode an uploaded QR code image
- Display the URL or text stored inside the QR code
- Simple and user-friendly web interface

## Technologies Used

- OpenCV
- Matplotlib
- Render
- GitHub
- JavaScript
- HTML
- CSS
- FastAPI

## Workflow

1. User opens the application.
2. User enters a URL or text.
3. The application generates a QR code.
4. User can scan the QR code using a mobile phone.
5. User can also upload a QR code image.
6. The application decodes the image and displays the stored information.

## How to Run

1. Clone this repository:
   ```bash
   git clone <your-repository-link>
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```


## Output

- QR code is generated successfully from the entered URL or text.
- Uploaded QR code images are decoded successfully.
- The application displays the original URL or text.

## Live Application

[https://qrcodepython.netlify.app/]

## Future Scope

- Add QR code download option
- Add logo customization inside the QR code
- Support Wi-Fi, contact, and UPI QR codes
- Add user login and QR code history

## Developed By

[Ajay Saware]
