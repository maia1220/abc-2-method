# ABC/2 Hematoma Volume Calculator

A simple, elegant, and clinically focused web-based calculator for estimating intracerebral hematoma volume using the **ABC/2 method**.

Designed for use in the **MINUTE Trial**.

---

## 🔬 About the ABC/2 Method

The ABC/2 method is a validated bedside estimation technique for intracerebral hemorrhage volume.

**Formula:**

Volume = A × B × C / 2

Where:

- **A** = Maximum length (cm)  
- **B** = Maximum width at 90° to A (cm)  
- **C** = Height (Number of CT slices with hematoma × slice thickness, typically 0.5 cm)  

**Reference:**  
[ABC/2 Method on Radiopaedia](https://radiopaedia.org/articles/abc2?lang=us)

---

## 🌐 Live Website

GitHub Pages deployment:  
[https://minute-abc2-calculator.netlify.app/](https://minute-abc2-calculator.netlify.app/)

---

## ✨ Features

- Automatic calculation of C (slice count × slice thickness)  
- Real-time volume computation  
- Last 5 calculation history table  
- PDF export of calculation results  
- Expandable **About the Tool** accordion with MINUTE Trial info  
- Terminal-style footer with 🛠, version, and hover-to-copy email  
- Favicon and mobile Apple touch icon  
- Progressive Web App (PWA) support: installable on mobile, offline-ready  

---

## 🧪 Designed For

This calculator was developed for the **MINUTE Trial**:  
[https://nihstrokenet.org/trials/minute/home](https://nihstrokenet.org/trials/minute/home)

---

## 🛠️ Technologies Used

- HTML5  
- Bootstrap 5  
- Custom CSS (Apple-style design)  
- Vanilla JavaScript  
- jsPDF (PDF generation)  
- GitHub Pages (deployment)  
- Service Worker + Manifest (PWA support)  

---

## 📦 Installation / Deployment

1. Clone the repository:

```bash
git clone https://github.com/mcally1220/abc-2-method.github.io.git

2. Ensure all files are in the repository root:
index.html
styles.css
favicon.png
manifest.json
sw.js

3. Open index.html in a browser, or deploy via GitHub Pages.

4. PWA support works automatically in modern browsers. On mobile, choose Add to Home Screen to install.

```

---

## ✅ What’s fixed/updated:  

- All headers and lists are properly formatted  
- Code blocks for Git commands and file lists  
- Inline code for filenames (`index.html`)  
- Bold and links correctly rendered  
- Clean, professional Markdown for GitHub  

---

## 📝 Version & Changes 
v1.0.0 (Feb 2026) 

- Initial release of ABC/2 Hematoma Volume Calculator
- Added automatic calculation of C (height)
- Added history table for last 5 entries
- Added PDF export of calculation results
- Added About the Tool accordion with MINUTE Trial info and reference link
- Added terminal-style footer with 🛠, version, and hover-to-copy email
- Added favicon and Apple touch icon
- Added Progressive Web App (PWA) support: offline caching, installable on mobile

---
## ⚠️ Disclaimer

This tool is intended for research and educational use only.  
Clinical decisions should always follow institutional protocols and professional medical judgment.

---

## 👩‍💻 Author

Built by Ally Qi © 2026  
All rights reserved.

Contact: mcally1220@gmail.com