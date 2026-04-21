# QR Code Studio

A lightweight web app to generate customizable QR codes from multiple data types such as URLs, WiFi credentials, contacts, emails, and locations. The app provides a clean interface with smooth interactions and allows users to download QR codes as high-quality PNG or PDF files.

Live demo: [QR Code Studio](https://drichdev.github.io/qrcodesite/)

## Technologies

* **HTML5** & **CSS3** — structure and modern UI styling
* **JavaScript (Vanilla)** — dynamic form handling and QR generation logic
* **QRious** — client-side QR code generation using canvas
* **jsPDF** — exporting QR codes as downloadable PDF files
* **Google Fonts (Space Mono)** — typography for a clean, technical aesthetic

---

## Features

* Generate QR codes for:

  * URLs
  * WiFi networks
  * Contacts (vCard)
  * Emails
  * Locations (Google Maps)
* Smooth animated UI transitions
* Styled QR preview with custom corner design
* Download options:

  * PNG (high quality)
  * PDF (centered layout)
* Fully client-side (no backend required)

---

## Usage

1. Select the type of data you want to convert
2. Fill in the required fields
3. Click **Generate**
4. Download your QR code as PNG or PDF

---

## Notes

* WiFi QR codes follow the standard format:
  `WIFI:T:WPA;S:NetworkName;P:Password;;`
* The app runs entirely in the browser — no data is stored or transmitted
