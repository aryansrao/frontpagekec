# KEC Lab Manual Creator

## Overview
KEC Lab Manual Creator is a web application designed to help students of Krishna Engineering College (KEC) easily generate professional lab manual cover pages. The project was inspired by the challenges faced by students who do not have access to laptops or consistent software environments, resulting in inconsistent and time-consuming manual cover creation. This tool streamlines the process, ensuring uniformity and accessibility for all students, regardless of their device or operating system.

## Motivation
Many students struggle to create custom front pages for their lab manuals due to:
- Lack of access to laptops or desktop computers.
- Differences in operating systems and available software, leading to inconsistent designs.
- Time-consuming manual formatting and editing.

KEC Lab Manual Creator solves these problems by providing a simple, device-independent web interface that generates standardized, attractive lab manual covers in seconds.

## Features
- **Responsive Design:** Works seamlessly on mobile devices, tablets, and desktops.
- **Step-by-Step Form:** Guides users through entering subject, student, and faculty details.
- **Live Validation:** Ensures all inputs are correct before generating the cover.
- **Preview Mode:** Allows users to review the generated cover before downloading.
- **PDF Download:** Generates a high-quality PDF of the cover page for easy printing or sharing.
- **Toast Notifications & Loading Animations:** Provides feedback and improves user experience.
- **Modern UI:** Uses gradients, icons, and animations for a professional look.
- **Progressive Web App (PWA):** Can be installed on your device for offline use and a native app-like experience.

## How It Works
1. **Fill the Form:** Enter all required details (subject, student, faculty, etc.).
2. **Preview:** Review the generated cover page for accuracy.
3. **Download:** Save the cover as a PDF, ready to print or submit.

## Technologies Used
- **HTML, CSS, JavaScript:** Core web technologies for structure, styling, and interactivity.
- **Font Awesome:** For modern icons.
- **Google Fonts (Poppins, Roboto):** For clean, readable typography.
- **html2canvas & jsPDF:** For rendering the cover and generating the PDF.
- **PWA Manifest & Service Worker:** Enables installation and offline capabilities.

## Folder Structure
```
frontpagekec/
├── index.html         # Main application file
├── keclogo.jpg        # College logo (used in the cover)
├── manifest.json      # PWA manifest
├── service-worker.js  # Service worker for offline support
```

## Usage
1. Open https://frontpagekec.netlify.app/ in any modern browser (Chrome, Firefox, Edge, Safari).
2. Fill in the required details in the form.
3. Click "Generate Lab Manual Cover".
4. Preview the cover page.
5. Download the PDF and print or share as needed.

## PWA Installation
- **On Desktop (Chrome/Edge):**
  1. Click the install icon in the address bar or open the browser menu and select "Install App".
  2. The app will be added to your desktop and can be launched like any other application.
- **On Mobile (Android/iOS):**
  1. Open the site in your browser.
  2. Tap the browser menu (three dots or share icon).
  3. Select "Add to Home Screen" or "Install App".
  4. The app icon will appear on your home screen for quick access and offline use.
- **Offline Use:**
  - Once installed, the app works offline and provides a native experience.

## Accessibility
- No installation required (unless you want offline/app experience).
- Works on any device with a browser (including smartphones).
- No dependencies on OS or external software.

## Contributing
Pull requests and suggestions are welcome! If you have ideas to improve accessibility, add new features, or fix bugs, feel free to contribute.

## License
This project is open-source and free to use for educational purposes.

## Author
Created by Aryan S. Rao, inspired by the needs of KEC students for a simple, unified solution to lab manual cover creation.

[![GitHub](https://img.shields.io/badge/GitHub-aryansrao-181717?logo=github)](https://github.com/aryansrao)

