# QR Code Generator App 🧾⚡

A fully browser-based QR Code Generator built with **React, Tailwind CSS, and QR Code Styling**, featuring:

- 🔐 User Signup/Login (localStorage-based)
- 🌐 URL validation
- 🎨 QR Code customization (color, style, marker types)
- 📥 PNG and PDF downloads
- 🕓 QR Code generation history

---

## ✨ Features

- **Authentication**: Sign up and log in with email/password (saved in localStorage).
- **URL Validation**: Only allows valid HTTP/HTTPS URLs.
- **Customization Options**:
  - QR Code color
  - Dots style: Square, Rounded, Dots
  - Marker styles: Border (Square, Rounded, Circle), Center (Square, Dot)
- **Generate & Download**:
  - Generate a styled QR Code on the fly
  - Download as PNG or PDF
- **History**:
  - Automatically stores your generated QR codes per user
  - View previous URLs and QR previews
- **Fully Client-side**: Works entirely in the browser. No backend required.

---

## 🛠️ Tech Stack

- **Frontend**: React (via CDN + Babel)
- **Styling**: Tailwind CSS
- **QR Code Library**: [qr-code-styling](https://github.com/kozakdenys/qr-code-styling)
- **PDF Download**: jsPDF
- **Data Persistence**: localStorage

---

## 🚀 How to Run Locally

1. Clone this repo:

```bash
git clone https://github.com/your-username/qr-code-generator-app.git
cd qr-code-generator-app
