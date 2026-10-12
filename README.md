 <p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:FFD6E7,50:F4B6D2,100:E8A6C8&height=180&section=header" width="100%" alt="Pastel pink header"/>
</p>

<h1 align="center">🎀 Resume Analyzer</h1>

<p align="center">
  <strong>A Client-Side Resume Evaluation System</strong>
</p>

<p align="center">
  Analyze resumes, identify technical skills, and receive structured feedback through a simple, responsive web application.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-Structure-E76F9A?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-Styling-D98CB3?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/JavaScript-Logic-C98DB8?style=for-the-badge&logo=javascript&logoColor=white" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/Architecture-Frontend%20Only-E8A6C8?style=for-the-badge" alt="Frontend only"/>
</p>

<p align="center">
  <em>Simple • Responsive • Privacy-conscious • Beginner-friendly</em>
</p>

---

## 🌸 Overview

**Resume Analyzer** is a frontend-based web application built with HTML5, CSS3, and vanilla JavaScript. It helps users review resumes by identifying relevant technical skills, checking keyword coverage, and generating structured feedback.

The application uses client-side processing to perform its analysis without requiring a dedicated application server.

### ✨ Why this project?

- Simplifies the initial resume-review process.
- Identifies technical skills using keyword matching.
- Provides an ATS-oriented assessment based on predefined rules.
- Demonstrates practical frontend development and JavaScript logic.
- Offers a lightweight interface without mandatory backend infrastructure.

---

## 💗 Key Features

| Feature | Description |
|---|---|
| 📄 Resume Upload | Select a supported resume file for analysis. |
| 🔍 Skill Detection | Identify technical skills using predefined keywords. |
| 📊 Resume Scoring | Generate a score based on implemented evaluation rules. |
| 📝 Structured Feedback | Present analysis results in an easy-to-understand format. |
| ⚡ Client-Side Processing | Perform supported operations directly in the browser. |
| 🎨 Responsive Interface | Designed for a straightforward user experience across screen sizes. |
| 🔒 Privacy-Conscious Design | No dedicated application server is required for client-side analysis. |

> **Note:** The actual supported file formats and analysis features depend on the implementation in `script.js`. A browser-only architecture does not automatically guarantee complete offline support or comprehensive PDF parsing.

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js" alt="HTML, CSS and JavaScript" />
</p>

| Technology | Purpose |
|---|---|
| HTML5 | Structures the application interface. |
| CSS3 | Handles layout, styling, responsiveness, and visual presentation. |
| JavaScript | Implements file handling, keyword detection, scoring, and feedback logic. |
| File API | Enables browser-based access to user-selected files. |

**Architecture:** Frontend-only application using vanilla JavaScript.

---

## 🏗️ System Architecture

<p align="center">
  <img src="https://img.shields.io/badge/01-Resume%20Upload-F4B6D2?style=flat-square" alt="Step 1"/>
  →
  <img src="https://img.shields.io/badge/02-Text%20Extraction-E8A6C8?style=flat-square" alt="Step 2"/>
  →
  <img src="https://img.shields.io/badge/03-Keyword%20Matching-D98CB3?style=flat-square" alt="Step 3"/>
  →
  <img src="https://img.shields.io/badge/04-Scoring-C98DB8?style=flat-square" alt="Step 4"/>
  →
  <img src="https://img.shields.io/badge/05-Feedback-E76F9A?style=flat-square" alt="Step 5"/>
</p>

```text
          USER
            |
            v
      Resume Upload
            |
            v
     File Processing
            |
            v
     Text Extraction
            |
            v
      Keyword Matching
            |
            v
      Scoring Logic
            |
            v
    Evaluation Results
            |
            v
     Structured Feedback
```

*The text-extraction stage depends on the file formats and parsing logic implemented in the project.*

---

## 📂 Project Structure

```text
resume-analyzer/
│
├── index.html       # Application structure
├── style.css        # Styling and responsive layout
├── script.js        # Resume analysis and scoring logic
├── assets/
│   └── demo.gif     # Optional application demonstration
│
└── README.md        # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser.
- Git installed on your system, if cloning the repository.
- A code editor such as Visual Studio Code (optional).

### Installation

**1. Clone the repository**

Replace `YOUR_USERNAME` with your GitHub username.

```bash
git clone https://github.com/YOUR_USERNAME/resume-analyzer.git
```

**2. Navigate to the project directory**

```bash
cd resume-analyzer
```

**3. Run the application**

Open `index.html` in your browser.

Alternatively, use the Live Server extension in Visual Studio Code for local development.

No backend server or database setup is required for the frontend-only version.

---

## 🎬 Demo

<p align="center">
  <img src="./assets/demo.gif" width="85%" alt="Resume Analyzer application demonstration"/>
</p>

<p align="center">
  <em>A preview of the resume evaluation workflow.</em>
</p>

> To display this section correctly, add your actual screen recording or GIF at `assets/demo.gif`. Otherwise, replace this section with a screenshot of the application.

---

## 🔐 Privacy and Security

The application is designed around client-side processing.

- Resume processing can take place within the browser.
- No dedicated application server or database is required by the frontend-only architecture.
- Users should review the implementation to confirm that resume contents are not transmitted to external services.
- Temporary file data should be cleared when it is no longer needed.

**Important:** Browser-side processing can improve privacy, but it is not a guarantee of complete security. Actual behavior depends on the code and any external libraries or services used.

---

## ⚠️ Current Limitations

- Keyword-based matching may miss relevant skills expressed in different wording.
- ATS-oriented scores are heuristic estimates, not official ATS scores.
- The quality of the analysis depends on the implemented scoring rules.
- PDF and DOCX support depends on the available text-extraction functionality.
- The current version does not provide advanced semantic analysis or AI-powered recommendations unless separately implemented.
- Resume evaluation does not guarantee selection or shortlisting by an employer.

---

## 🔮 Future Enhancements

- [ ] Job description matching and relevance scoring.
- [ ] Skill-gap analysis with actionable recommendations.
- [ ] PDF and DOCX text extraction support.
- [ ] Semantic matching using NLP.
- [ ] AI-assisted resume feedback.
- [ ] Downloadable analysis reports.
- [ ] Resume section detection and completeness checks.
- [ ] Accessibility improvements and dark mode.
- [ ] Automated testing and improved error handling.

---

## 💡 Learning Outcomes

Through this project, the following development concepts can be explored:

- DOM manipulation and event handling.
- Browser File API and client-side file processing.
- String processing and keyword-matching algorithms.
- Rule-based scoring and feedback generation.
- Responsive web design.
- Organizing a frontend project into separate files.
- Writing technical documentation with Markdown.

---

## 👩‍💻 Author

**Shruti Sinha**

B.Tech Computer Science and Engineering student interested in software development, data analytics, and AI/ML.

<p align="center">
  <a href="https://github.com/Shrutishinha">
    <img src="https://img.shields.io/badge/GitHub-Profile-E8A6C8?style=for-the-badge&logo=github&logoColor=white" alt="GitHub profile"/>
  </a>
</p>

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

<p align="center">
  <em>Built with curiosity, code, and a little pastel pink. 🌷</em>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:FFD6E7,50:F4B6D2,100:E8A6C8&height=100&section=footer" width="100%" alt="Pastel pink footer"/>
</p>
