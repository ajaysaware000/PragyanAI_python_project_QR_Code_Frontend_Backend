# QR Code Generator and Decoder

A Python-based web application that allows users to generate QR codes from text or URLs and decode existing QR code images.

## 🔗 Project Links

- **GitHub Repository:** https://github.com/ajaysaware000/PragyanAI_python_project_QR_Code_Frontend_Backend
- **Live Application:** https://qrcodepython.netlify.app/

## 📌 Project Overview

The QR Code Generator and Decoder is a web-based application designed to simplify the process of creating and reading QR codes. Users can enter text or URLs to generate QR codes and upload existing QR code images to retrieve their encoded information.

This project demonstrates the practical application of Python, image processing, frontend development, backend development, and web deployment.

## ❗ Problem Statement

Sharing long URLs or text manually can be time-consuming and may lead to typing errors. Similarly, extracting information from QR codes requires a suitable decoding tool.

This project provides a simple solution for generating QR codes and decoding existing QR code images through a user-friendly web interface.

## 🎯 Objectives

- To develop a web application for QR code generation and decoding.
- To convert text and URLs into QR codes.
- To extract information from uploaded QR code images.
- To provide a simple and user-friendly interface.
- To implement Python programming and image-processing concepts.
- To understand frontend-backend integration and web deployment.

## ✨ Features

### 1. QR Code Generation

- Generate QR codes from text and URLs.
- Convert website links into scannable QR codes.
- Display generated QR codes on the interface.

### 2. QR Code Decoding

- Upload existing QR code images.
- Detect and decode supported QR codes.
- Display the extracted text or URL.

### 3. User-Friendly Interface

- Simple and intuitive interface.
- Easy navigation between generation and decoding features.
- Convenient access through a web browser.

### 4. Deployment

- Frontend hosting using Netlify.
- Backend deployment using Render.
- Source code management using GitHub.

## 🛠️ Technologies Used

- **Python** – Core application logic.
- **OpenCV** – QR code detection and decoding.
- **FastAPI** – Backend API development.
- **HTML** – Web page structure.
- **CSS** – Interface styling.
- **JavaScript** – Frontend interactions.
- **Git** – Version control.
- **GitHub** – Source code hosting.
- **Netlify** – Frontend deployment.
- **Render** – Backend deployment.

*Note: Verify the technologies against the actual source code before publishing this section.*

## 🔄 How It Works

1. The user opens the web application.
2. The user enters text or a URL to generate a QR code.
3. The application processes the input and displays the QR code.
4. Alternatively, the user uploads an existing QR code image.
5. The backend processes the image and attempts to decode it.
6. The extracted information is displayed to the user.

## 📁 Project Structure

```text
PragyanAI_python_project_QR_Code_Frontend_Backend/
│
├── Backend/
│   └── config.json
│   └── main.py
│   └── requirements.txt
│   └── utils.py
├── Frontend/
│   └── index.html
│   └── script.js
│   └── style.js
│
├── .gitignore
├── .python-version
└── README.md
```

*Note: This is a simplified structure. Refer to the repository for the actual files.*

## 💻 Installation and Setup

### Prerequisites

- Python 3
- Git
- Visual Studio Code or another code editor
- A modern web browser

### Step 1: Clone the Repository

```bash
git clone https://github.com/ajaysaware000/PragyanAI_python_project_QR_Code_Frontend_Backend.git
```

### Step 2: Navigate to the Project Directory

```bash
cd PragyanAI_python_project_QR_Code_Frontend_Backend
```

### Step 3: Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment on Windows:

```bash
venv\Scripts\activate
```

### Step 4: Install Dependencies

If the backend contains a `requirements.txt` file, install the dependencies using its actual path.

```bash
pip install -r Backend/requirements.txt
```

### Step 5: Run the Backend

For a FastAPI application, a typical command is:

```bash
uvicorn main:app --reload
```

Replace `main:app` with the correct module and application name used in your project.

### Step 6: Run the Frontend

Run the frontend using the command appropriate for its framework. For example, if it uses Streamlit:

```bash
streamlit run app.py
```

Replace `app.py` with the actual entry-point filename.

**Note:** The commands above are examples. Confirm the correct dependency file and startup commands in your repository before running the application.

## 📖 Usage

### Generate a QR Code

1. Open the application.
2. Enter text or a URL.
3. Select the QR code generation option.
4. View the generated QR code.
5. Scan the QR code using a compatible scanner.

### Decode a QR Code

1. Open the QR code decoding section.
2. Upload an image containing a QR code.
3. Wait for the application to process the image.
4. View the decoded information.

## ✅ Expected Output

- QR code generated from text or a URL.
- QR code displayed on the web interface.
- Information extracted from uploaded QR code images.
- A simple interface for generating and decoding QR codes.

## 🔮 Future Enhancements

- Download QR codes as PNG or JPG images.
- Customize QR code colors and sizes.
- Add logos to generated QR codes.
- Support Wi-Fi credentials and contact information.
- Maintain a history of generated QR codes.
- Improve error handling and validation.
- Add automated testing and security improvements.

## 📚 Learning Outcomes

- Python programming.
- QR code generation and decoding.
- Image processing with OpenCV.
- Frontend and backend integration.
- API development.
- Git and GitHub version control.
- Web application deployment.
- Software testing and documentation.

## 👨‍💻 Author

**Ajay Saware**

- GitHub Profile: https://github.com/ajaysaware000
- Project Repository: https://github.com/ajaysaware000/PragyanAI_python_project_QR_Code_Frontend_Backend

---

⭐ If you find this project useful, consider giving the repository a star!

**Built with Python to make QR code generation and decoding simple.**
