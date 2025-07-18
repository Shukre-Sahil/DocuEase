# DocuEase OCR Web App
A lightweight web application for seamless text extraction from images.


**Simplifying Document Digitization through OCR**

[![Netlify Status](https://api.netlify.com/api/v1/badges/31707da4-6642-41fe-934e-a9c755c87a28/deploy-status)](https://app.netlify.com/projects/docuease-ss/deploys)

## 🚀 Live Demo

- **Frontend:** [DocuEase on Netlify]([https://docuease-ss.netlify.app/](https://docuease-ss.netlify.app/))
- **Backend API:** [Flask API on Render](https://ocr-backend-gr8w.onrender.com)

---

## 📝 Project Overview

DocuEase is a web-based Optical Character Recognition (OCR) platform that extracts text from images in **English, Hindi, and Marathi**, enabling rapid document digitization for students, businesses, and researchers.

---

## ⚙️ Tech Stack

- **Frontend:** React.js (JavaScript, HTML, CSS)
- **Backend:** Flask, Python, Tesseract OCR
- **Deployment:**
  - Frontend – Netlify
  - Backend – Render

---

## 🏗️ System Architecture
User Uploads Image (Frontend React)
↓
POST request via Axios
↓
Flask Backend (Render) receives image + language
↓
Tesseract OCR processes the image
↓
Returns extracted text as JSON response
↓
Frontend displays text in textarea


---

## 💻 Implementation Details

### **Frontend**
- Built using **React.js functional components and hooks**.
- Features:
  - File upload input
  - Language selection dropdown
  - Dark mode toggle
  - Responsive, aesthetic UI with neon theme.

### **Backend**
- Developed with **Flask**.
- Uses **Tesseract OCR** for multi-language text extraction.
- REST API with `/ocr` POST endpoint.

### **Deployment**
- **Frontend** deployed on **Netlify** for fast static serving.
- **Backend** deployed on **Render** for scalable API hosting.

---

## 🚧 Limitations

- Cold start delay (~10-30 sec) if backend is inactive for >15 min.
- Accuracy depends on image clarity and supported fonts.
- Limited concurrency due to free hosting plan constraints.

---

## 🔮 Future Scope

- Expand to PDF and document file uploads.  
- Add database to save extracted texts.  
- Enhance UI animations and dark mode theming.  
- Integrate user authentication for personal document management.

---

## 👤 Developer

**Sahil Shukre**

Connect on [LinkedIn](www.linkedin.com/in/sahil-shukre-269961281) | GitHub: [Shukre-Sahil](https://github.com/Shukre-Sahil)

---

## 📜 License

This project is open source under the [MIT License](LICENSE).

---

> ⚡ **Note:**  
> Backend API is designed for integration/testing. Users should interact via the frontend app link for best experience.



