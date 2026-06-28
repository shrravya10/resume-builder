# 📄 Resume Builder

A sleek, browser-based Resume Builder that lets you create, customize, and download a professional resume — no sign-up required.

---

## 🚀 Features

- **Live Preview** — See your resume update in real time as you type
- **Customizable Sections** — Add your personal info, education, experience, skills, and more
- **Download as PDF** — Export your resume instantly
- **No Backend Required** — Runs entirely in the browser; Express just serves the static file
- **Responsive Design** — Works on desktop and mobile

---

## 🛠️ Tech Stack

| Layer    | Technology            |
|----------|-----------------------|
| Frontend | HTML, CSS, JS |
| Backend  | Node.js + Express     |

---

## 📁 Project Structure

```
resume-builder/
├── index.html          # Frontend UI — resume form and live preview
├── server.js           # Express server to serve the static frontend
├── package.json        # Project metadata and start script
├── package-lock.json   # Locked dependency versions
└── .gitignore          # Excludes node_modules and system files
```

---

## ⚙️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or above)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/shrravya10/resume-builder.git
cd resume-builder

# 2. Install dependencies
npm install

# 3. Start the server
npm start
```

Then open your browser and visit:

```
http://localhost:8080
```

---

## 📸 Usage

1. Fill in your **personal details** — name, email, phone, LinkedIn, etc.
2. Add your **education**, **work experience**, and **skills**
3. Watch the **live preview** update as you type
4. Click **Download / Export** to save your resume as a PDF

---

## 🔧 Configuration

The server runs on port **8080** by default. Override it with an environment variable:

```bash
PORT=3000 npm start
```

---

## 📌 Notes

- All resume data stays in your browser — nothing is sent to any server
- The Express server only serves the `index.html` file; no database or API involved
- To share your resume, use the PDF export feature

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
