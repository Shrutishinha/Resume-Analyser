📄 Resume Analyzer
HTML • CSS • JavaScript (Frontend Project)

A browser-based Resume Analyzer built using HTML, CSS, and Vanilla JavaScript.
The application performs client-side, keyword-based resume analysis to evaluate technical skill presence and provide basic improvement suggestions — without using any backend, AI, or external libraries.

✅ All processing happens locally in the browser
❌ No AI/ML or server-side processing (by design)

✨ Key Highlights

⚡ Fully frontend (no backend required)

📂 Upload or paste resume content

🔍 Skill & keyword detection

📊 Basic resume scoring logic

🧠 ATS-oriented keyword checks

💡 Improvement suggestions

🎨 Clean, responsive UI

🧠 How the Resume Analysis Works

The analysis is rule-based and deterministic, implemented entirely in JavaScript:

Resume text is read using the FileReader API

Text is normalized (lowercase, cleaned symbols)

Keywords are matched against predefined skill sets

A score is calculated based on matched skills

Missing or weak areas are identified

Results are dynamically rendered on the UI

This approach helps demonstrate JavaScript logic, DOM manipulation, and text processing fundamentals.

🛠️ Tech Stack
Technology	Purpose
HTML5	Structure & layout
CSS3	Styling & responsiveness
JavaScript (ES6)	Analysis logic & DOM updates
FileReader API	Reading resume files
📁 Project Structure
resume-analyzer/
│
├── index.html       # Main UI

├── style.css        # Styling & layout

├── script.js        # Resume analysis logic

├── assets/          # Images / icons

└── README.md

📊 Skills Evaluated (Configurable)

HTML, CSS, JavaScript

React (keyword-based)

Java, Python

SQL, MongoDB

Git & GitHub

Data Structures (basic terms)

Skill lists and scoring weights can be modified inside script.js.

🖥️ Run Locally
git clone https://github.com/your-username/resume-analyzer.git
cd resume-analyzer


Open index.html in any modern browser.

✔ No setup
✔ No dependencies
✔ Works offline

🎯 Intended Use

Frontend development practice

Academic / mini-project submission

Understanding client-side file handling

Demonstrating JavaScript logic & UI skills

Portfolio project for beginners–intermediate level

⚠️ Limitations (Transparent)

Keyword-based analysis only

No semantic or contextual understanding

No OCR or scanned PDF support

No real ATS or recruiter system integration

No machine learning or NLP

🔮 Future Scope

Job description vs resume comparison

Enhanced PDF text extraction

Custom role-based skill selection

Downloadable analysis report

Backend integration (Node.js)

👩‍💻 Author

Shruti
Frontend Developer
Skills: HTML • CSS • JavaScript • Data Analysis

⭐ Support

If you find this project useful or insightful, consider giving it a ⭐ on GitHub.
