# Build A Resume

A free, responsive resume builder designed to help you create professional, ATS-friendly resumes with a live preview and PDF export. Customize your information, choose your preferred paper size, and build a resume that suits your needs.

## ✨ Features

- **Live Resume Preview** — See your changes as you edit your resume.
- **ATS-Friendly Layout** — Create a clean, text-focused resume designed with applicant tracking systems in mind. ATS compatibility is not guaranteed for every system.
- **Customizable Sections** — Add and edit personal information, contact details, professional profile, skills, work experience, education, certificates, and references.
- **Section Visibility Controls** — Choose which information appears in your final resume.
- **Photo Support** — Optionally upload a profile photo for your resume.
- **Multiple Paper Sizes** — Choose from A4, Letter, Legal, and A3.
- **PDF Export** — Download your finished resume as a PDF.
- **Print Support** — Print your resume directly from your browser.
- **Automatic Saving** — Resume information is saved locally in your browser.
- **Dark and Light Mode** — Switch between black-and-white themes for a comfortable editing experience.
- **Responsive Design** — Use the editor on desktop, tablet, and mobile devices.
- **Demo Resume** — Explore the available features using sample resume information.
- **Privacy-Focused Storage** — No account or database is required for the current browser-based functionality.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Browser Local Storage
- [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) for PDF generation

## 🚀 Getting Started

### Prerequisites

- A modern web browser with JavaScript enabled.
- An internet connection for loading the PDF generation library from its configured CDN.
- PHP is optional for the current browser-based functionality, but you can use a PHP server if you keep the entry file named `index.php`.

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/build-a-resume.git
   ```

2. Navigate to the project directory:

   ```bash
   cd build-a-resume
   ```

3. Run the application locally using one of the following methods.

   **Using PHP:**

   ```bash
   php -S localhost:8000
   ```

   Then visit [http://localhost:8000](http://localhost:8000).

   **Using a static web server:**

   If you rename `index.php` to `index.html`, you can serve the application through a static web server without PHP.

4. Start creating your resume, customize the sections, preview the result, and export your resume as a PDF.

## 📁 Project Structure

The project can remain a single-file application, with supporting assets placed alongside the entry file.

```text
build-a-resume/
├── index.php       # Main application
├── index.html      # Optional alternative for static hosting
├── icon.png        # Optional brand icon
├── gcash.jpg       # Optional donation QR image
├── README.md       # Project documentation
└── LICENSE         # MIT License
```

**Note:** Use either `index.php` or `index.html` as your main entry file, depending on your hosting setup. The `gcash.jpg` file is optional and is only needed if you enable the donation QR feature.

## 🔒 Privacy and Data Storage

Build A Resume currently stores resume information and theme preferences in your browser's local storage.

- No account is required to use the current browser-based application.
- Resume information is not automatically synchronized between devices or browsers.
- Clearing browser storage may permanently remove your locally saved resume.
- Anyone with access to the same browser profile may be able to access its locally stored resume data.
- PDF generation relies on a third-party JavaScript library loaded from a CDN.
- Export a PDF backup if you need to keep your resume independently of browser storage.

Avoid entering sensitive personal information on shared or public computers.

## 📄 License

This project is licensed under the **MIT License**.

You are permitted to use, copy, modify, merge, publish, distribute, sublicense, and sell copies of the software, subject to the conditions of the license.

See the [LICENSE](LICENSE) file for the complete terms.

Third-party libraries and assets may be subject to their own licenses and terms.

## 🤝 Contributions

Suggestions, bug reports, and improvements are welcome.

Before submitting changes, please test the main functionality, including:

- Resume editing and live preview
- Local storage and data restoration
- Theme switching
- Responsive layouts
- Printing and PDF export

## 👨‍💻 Author

**Renzo Lazarte**

Personal portfolio: [renzolazarte.freedev.app](https://renzolazarte.freedev.app/)

---

Built with care by Renzo Lazarte. Free to use under the MIT License.
